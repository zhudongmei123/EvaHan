<div align='center'>
<img src = 'https://user-images.githubusercontent.com/54113513/201254029-e63dd695-22aa-4419-ac01-7fc34326625a.png'>
</div>

# Important Notice
-   

# EvaHan 2026

-   EvaHan 2026 is the Fifth International Evaluation of Ancient Chinese Information Processing, focusing on OCR tasks for multimodal large language models in ancient Chinese.
-   Co-organized with LREC 2026, which will be held from May 11 to 16, 2026, in Mallorca, Spain.
-   EvaHan 2026 is organized by Dongbo Wang, Bin Li, Minuxan Feng, Chao Xu, Weiguang Qu, Liu Liu, Si Shen.


## Previous Tasks
- EvaHan2022
  - The First bakeoff of ancient Chinese automatic processing, was successfully held in Marseille, France, in 2022, with a focus on **automatic word segmentation and part-of-speech tagging of ancient Chinese**.
- EvaHan2023
  - The Second bakeoff of ancient Chinese automatic processing, was successfully held in Macau, China, in 2023, with a focus on **machine translation of ancient Chinese**.
- EvaHan2024
  - The Third bakeoff of ancient Chinese automatic processing, was held in Turin, Italy, in 2024, with a focus on **automatic sentence segmentation and punctuation of ancient Chinese**.
- EvaHan2025
  - The Fourth bakeoff of ancient Chinese automatic processing, was held  in New Mexico, USA, in 2025, with a focus on named entity recognition in ancient Chinese.



## Important Dates for EvaHan 2026

- **Registration deadline**: January 30, 2026  
- **Training data release**: January 1, 2026 
- **Test data release**: February 1, 2026  
- **Running results submission**: February 6, 2026  
- **Technical report submission deadline**: February 28, 2026  
- **Notification of acceptance**: March 1, 2026  
- **Camera-ready papers due**: March 10, 2026  

## Participation

To participate in **EvaHan 2026**, you must complete the following steps:

1. **Registration**:  
   Submit a registration form to officially register your team for the task. Registration is open from December 1, 2025, to January 15, 2026. Only registered participants will gain access to the training dataset.

2. **Accessing the Training Data**:  
   After completing the registration process, participants will receive instructions for downloading the training dataset, which includes image–text pairs from ancient Chinese texts for OCR. 

3. **Submitting Results and Reports**:  
   Participants must use the provided test data to generate results and submit their system outputs and a technical report as per the shared task schedule.

For inquiries or to request the registration form, please contact us at TBD.


# Data
The Evahan 2026 dataset comprises three datasets, covering image-text pairs: plain text images, mixed image-text images, and handwritten images-text. The data underwent initial automatic annotation, followed by meticulous correction and refinement by experts in classical Chinese language and history to ensure the highest quality of the training materials and gold-standard texts.

- **Dataset A**  consists of data selected from the Siku Quanshu (Complete Library of the Four Treasuries), including classics, history, philosophy, and literature, as well as various other ancient books.

- **Dataset B**  contains mixed image-text data selected from the Siku Quanshu and other ancient books.


- **Dataset C** includes handwritten ancient books, primarily the Chinese Buddhist canon, including the Korean Buddhist canon, the Chinese Buddhist canon (TKH) dataset, and the Chinese Buddhist canon (MTH) dataset.

## Data Format
All evaluation data are in the form of image-text pairs, and the text is a txt file in Unicode (UTF-8) format. The specific format is shown in Table 1。


## Training Data
The training data consists of three datasets, all in the form of image-text pairs. The text is in traditional Chinese UTF-8 plain text format. After registration, the training data will be sent to your email address. 

## Test Data
The test data also consists of three datasets, also in the form of image-text pairs. More details will be provided to participants before the evaluation. Download links will be available soon.

# Task
This section offers a detailed description of the tasks encompassed in EvaHan 2026.
In many Chinese language processing systems, optical character recognition (OCR) is a critical task, often performed in parallel with other processing functions. The accuracy and speed of OCR directly determine the overall system's performance and user experience in downstream applications such as document digitization, information extraction, and intelligent retrieval.

# Evaluation

## Metrics
Each team will only have access to the training data. Later, unlabeled test data will also be released. After the evaluation is complete, the labels for the test data will also be released. Tables 2 and 3 provide examples of the scorer output. The evaluation will align the system-generated named entities with the gold standard. Next, OCR will be evaluated: precision, recall, and F1 score will be calculated. BLEU ROUGE-1, ROUGE-2, and ROUGE-L will also be evaluated, bringing the competition's evaluation to multiple metrics. The final ranking of teams will be based on the combined scores.
Table 2. Example of scorers' output





## Two Modalities
Each participant can submit results for both modes. In the closed mode, each team has limited resources. Each team can only use training data and a pre-trained model. This model is a word embedding pre-trained on a large Traditional Chinese corpus. No other resources are allowed in the closed mode. 
In the open mode, there are no restrictions on resources, data, or models. Annotated external data, such as processed images or text, may be used. However, each team must disclose all resources, data, and models used in each system in the final report.


## Baselines
As a baseline, we will provide the scores obtained on test set using Xunzi_MLLM_minicip_2.6 training on train set without additional resources.

# How to Participate
Registration time is mentioned above. Participants will be required to submit their runs and to provide a technical report for the task they participated in.

## Submitting Runs




## Writing the Technical Report




# Participants
●Researchers interested in ancient book OCR based on machine learning and multimodal large models.


# Organizers

- **Dongbo Wang**, College of Information Management, Nanjing Agricultural University, China

- **Bin Li**, School of Chinese Language and Literature, Nanjing Normal University, China

- **Minxuan Feng**, School of Chinese Language and Literature, Nanjing Normal University, China

- **Chao Xu**, School of Chinese Language and Literature, Nanjing Normal University, China

- **Weiguang Qu**, School of Computer and Electronic Information /School of Artificial Intelligence, Nanjing Normal University, China

- **Liu Liu**, College of Information Management, Nanjing Agricultural University, China

- **Si Shen**, School of Economics and Management, Nanjing University of Science and Technology, China



# Student Members

- **Dongmei Zhu**, College of Information Management, Nanjing Agricultural University, China

- Jieqiong Li, College of Information Management, Nanjing Agricultural University, China

- Ruifeng Wu,College of Information Management, Nanjing Agricultural University, China

- Junyi Yang，College of Information Management, Nanjing Agricultural University, China

- Yue Zhu, School of Chinese Language and Literature, Nanjing Normal University, China

- Junjie Li, School of Chinese Language and Literature, Nanjing Normal University, China

- Zhixing Xu, School of Chinese Language and Literature, Nanjing Normal University, China




# Appendix: Selection of Resources
For more information about the EvaHan shared task and the ALP2025 workshop, visit the official ALP2026 webpage.
OCR Model  
●DeepSeek-OCR: https://www.modelscope.cn/models/deepseek-ai/DeepSeek-OCR
●PaddleOCR-VL: https://www.modelscope.cn/models/PaddlePaddle/PaddleOCR-VL
●mscoder/duguang-ocr-onnx-v2: https://www.modelscope.cn/models/mscoder/duguang-ocr-onnx-v2
●RapidAI/RapidOCR: https://www.modelscope.cn/models/RapidAI/RapidOCR
●iic/cv_convnextTiny_ocr-recognition-document_damo: https://www.modelscope.cn/models/iic/cv_convnextTiny_ocr-recognition-document_damo





 
