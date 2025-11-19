# <img src="media/image1.png" alt="logo-EvaHan" width="553">

## EvaHan2026

## 

-   EvaHan 2026 is the Fifth International Evaluation of Ancient Chinese
    Information Processing, focusing on OCR tasks for multimodal large
    language models in ancient Chinese.

-   Co-organized with LREC 2026, which will be held from May 11 to 16,
    2026, in Mallorca, Spain.

-   EvaHan 2026 is organized by Dongbo Wang, Bin Li, Minuxan Feng, Chao
    Xu, Weiguang Qu, Liu Liu, Si Shen.

## Previous Tasks

-   EvaHan2022

The first bakeoff of ancient Chinese automatic processing, was
successfully held in Marseille, France, in 2022, with a focus
on automatic word segmentation and part-of-speech tagging of ancient
Chinese.

-   EvaHan2023

The second bakeoff of ancient Chinese automatic processing, was
successfully held in Macau, China, in 2023, with a focus on machine
translation of ancient Chinese.

-   EvaHan2024

The third bakeoff of ancient Chinese automatic processing, was held in
Turin, Italy, in 2024, with a focus on automatic sentence segmentation
and punctuation of ancient Chinese.

-   EvaHan2025

The fourth bakeoff of ancient Chinese automatic processing， was held in
New Mexico, USA,in 2025, with a focus on named entity recognition in
ancient Chinese.

## Important Dates for EvaHan 2026

-   Registration deadline: January 30, 2026

-   Training data release: January 1, 2026

-   Test data release: February 1, 2026

-   Running results submission: February 6, 2026

-   Technical report submission deadline: February 28, 2026

-   Notification of acceptance: March 1, 2026

-   Camera-ready papers due: March 10, 2026

## Participation

To participate in EvaHan 2026, you must complete the following steps:

1.**Registration:**\
Submit a registration form to officially register your team for the
task. Registration is open from December 1, 2025, to January 30, 2026.
Only registered participants will gain access to the training dataset.

2.**Accessing the Training Data:**\
After completing the registration process, participants will receive
instructions for downloading the training dataset, which includes
image--text pairs from ancient Chinese texts for OCR.

3.**Submitting Results and Reports:**\
Participants must use the provided test data to generate results and
submit their system outputs and a technical report as per the shared
task schedule.

For inquiries or to request the registration form, please contact us
at [evahan2026@gmail.com](mailto:evahan2025@gmail.com).

**Data**

The Evahan 2026 dataset comprises three datasets, covering image-text
pairs: plain text images, mixed image-text images, and handwritten
images-text. The data underwent initial automatic annotation, followed
by meticulous correction and refinement by experts in classical Chinese
language and history to ensure the highest quality of the training
materials and gold-standard texts.

● Dataset A consists of data selected from the *Siku Quanshu* (Complete
Library of the Four Treasuries), including classics, history,
philosophy, and literature, as well as various other ancient books.

● Dataset B contains mixed image-text data selected from the *Siku
Quanshu* and other ancient books.

● Dataset C includes handwritten ancient books, primarily the Chinese
Buddhist canon, including the Korean Buddhist canon, the Chinese
Buddhist canon (TKH) dataset, and the Chinese Buddhist canon (MTH)
dataset.

**Data Format**

## All evaluation data are in the form of image-text pairs, and the text is a txt file in Unicode (UTF-8) format. The specific format is shown in Table 1。

##  Table 1. Ancient Chinese OCR Corpus Example

| picture | text |
|---------|------|
| <img src="media/image2.png" alt="1761273613524" width="192"> | 欽定四庫全書     史部十一\\n 三呉水考       地理類四{{河渠之屬/}}\\n  提要\\n    {{臣/}}等謹案三呉水考十六卷明張内藴周大\\n    韶仝撰内藴稱呉江生員大韶稱華亭監生\\n    其始末則均未詳也初萬厯四年言官論蘇\\n    松常鎮諸府水利久湮宜及時修濬乞遣御\\n    史一員督其事乃命御史懷安林應訓往應 |
| <img src="media/image3.png" alt="descript" width="233"> | 四夫治洫\\n              廣八尺深八尺曰洫\\n              廣二尋深二仞曰澮\\n              同間有澮\\n              註云方百里為同同中容\\n              四都六十四成方八十里\\n              出田稅縁邊十里治澮\\n              井田之制備於一同 |
| <img src="media/image4.png" alt="" width="293"> | 言卽眼識界若有爲若無爲增語是\\n 菩薩摩訶薩卽耳鼻舌身意識界若\\n 有爲若無爲增語是菩薩摩訶薩善\\n 現汝復觀何義言卽眼識界若有漏\\n 若無漏增語非菩薩摩訶薩卽耳鼻\\n 舌身意識界若有漏若無漏增語非\\n 菩薩摩訶薩耶世尊若眼識界有漏\\n 無漏若耳鼻舌身意識界有漏無漏\\n 尚畢竟不可得性非有故況有眼識\\n 界有漏無漏增語及耳鼻舌身意識\\n 界有漏無漏增語此增語旣非有如\\n 何可言卽眼識界若有漏若無漏增\\n 語是菩薩摩訶薩卽耳鼻舌身意識\\n 界若有漏若無漏增語是菩薩摩訶\\n 鼻...... |

**Training Data**

# The training data consists of three datasets, all in the form of image-text pairs. The text is in traditional Chinese UTF-8 plain text format. After registration, the training data will be sent to your email address. 

# Test Data 

The test data also consists of three datasets, also in the form of
image-text pairs. More details will be provided to participants before
the evaluation. Download links will be available soon.

# Task

This section offers a detailed description of the tasks encompassed in
EvaHan 2026.

**OCR**

In many Chinese language processing systems, optical character
recognition (OCR) is a critical task, often performed in parallel with
other processing functions. The accuracy and speed of OCR directly
determine the overall system\'s performance and user experience in
downstream applications such as document digitization, information
extraction, and intelligent retrieval.

# Evaluation

# Metrics

Each team will only have access to the training data. Later, unlabeled
test data will also be released. After the evaluation is complete, the
labels for the test data will also be released. Tables 2 and 3 provide
examples of the scorer output. The evaluation will align the
system-generated text with the gold standard. Next, OCR will
be evaluated: accuracy, recall, and F1 score will be calculated. BLEU
ROUGE-1, ROUGE-2, and ROUGE-L will also be evaluated, bringing the
competition\'s evaluation to multiple metrics. This evaluation adds layout analysis metrics: mAP and IoU. T
he team's final ranking will be based on the overall score. The final ranking of
teams will be based on the combined scores.

Table 2. Example of scorers' output

| Task | BLEU | ROUGE-1 | ROUGE-2 | ROUGE-L |
|------|------|---------|---------|---------|
| OCR  | 52.75 | 73.98  | 63.89   | 72.17   |

Table 3. Example of scorers' output

| Task | Accuracy | Recall | F1_Score |
|------|----------|--------|----------|
| OCR  |  52.75   | 73.98  |  63.89   |

Table 4. Example of scorers' output

|         Task         |   mAP    | IoU    | 
|----------------------|--------- |--------|
| Page Layout Analysis |  88.20   | 89.00  | 


# Two Modalities

Each participant can submit results for both modes. In the closed mode,
each team has limited resources. Each team can only use training data
and a pre-trained model. This model is a word embedding pre-trained on a
large Traditional Chinese corpus. No other resources are allowed in the
closed mode.

## In the open mode, there are no restrictions on resources, data, or models. Annotated external data, such as processed images or text, may be used. However, each team must disclose all resources, data, and models used in each system in the final report.

# Baselines

As a baseline, we will provide the scores obtained on test set using
Xunzi_Qwen2_VL_7B_Instruct training on train set without additional
resources.

# How to Participate

Registration time is mentioned above. Participants will be required to
submit their runs and to provide a technical report for the task they
participated in.

## Submitting Runs（提交2次结果，提交源代码，复测）

Each team can submit runs for two tasks. A run should be produced
according to the closed modality. The second run will be produced
according to the open modality. The closed run is compulsory, while the
open run is optional.

Once the system has produced the results for the task over the test set,
participants have to follow these instructions to complete their
submission:

-   The annotated results should be submitted as three plain text files
    encoded in UTF-8 (four-byte encoding).The output format is shown in
    Table 4 (the names of the test data images cannot be modified).

Table 4. Example of format' output

| Format |
|--------|
| { "image_name": " xxx.png", "ocr_result ": "xxxxxxx"} |

-   Please submit the annotated test set results via
    [evahan2026@gmail.com](mailto:evahan2025@gmail.com). before February
    6, 2026, 23:59 (UTC-8).

-   Two submissions are allowed before the deadline. However, the final
    score will be based solely on the last submission.

-   Submit your trained code via email so the organizers can reproduce
    the results.

# Writing the Technical Report（比赛结果，没有报告不予承认）

All the reports must:

Technical reports will be included in the proceedings of the **third
Workshop on Ancient Language Processing (ALP2026)**, co-located with
NAACL 2025, which will take place from May 11 to 16，2026, inMallorca,
Spain. The reports will be published as short papers alongside the NAACL
proceedings.

• be submitted through the START platform (URL will be announced on
the [ALP2026
webpage](https://www.ancientnlp.com/alp2025/call_for_papers/))

• use the [official ACL style
templates](https://acl-org.github.io/ACLPUB/formatting.html)

• not exceed four (4) pages of content (excluding references)

• include (at least) the following sections: description of the system,
results, discussion, and references.

Reports will undergo a light review process to ensure correctness of the
format, accuracy of results and rankings, and clarity of exposition. If
necessary, authors will be contacted for corrections prior to
publication.

# Participant

-   Researchers interested in ancient book OCR based on machine learning
    and multimodal large models.

# Organizers

-   **Dongbo Wang**, College of Information Management, Nanjing
    Agricultural University, China

```{=html}
<!-- -->
```
-   **Bin Li**, School of Chinese Language and Literature, Nanjing
    Normal University, China

-   **Minxuan Feng**, School of Chinese Language and Literature, Nanjing
    Normal University, China

-   **Chao Xu**, School of Chinese Language and Literature, Nanjing
    Normal University, China

-   **Weiguang Qu**, School of Computer and Electronic Information
    /School of Artificial Intelligence, Nanjing Normal University, China

-   **Liu Liu**, College of Information Management, Nanjing Agricultural
    University, China

-   **Si Shen**, School of Economics and Management, Nanjing University
    of Science and Technology, China

# Student Members

-   **Dongmei Zhu**, College of Information Management, Nanjing
    Agricultural University, China

-   **Jieqiong Li**, College of Information Management, Nanjing
    Agricultural University, China

-   Ruifeng Wu,College of Information Management, Nanjing Agricultural
    University, China

-   Junyi Yang，College of Information Management, Nanjing Agricultural
    University, China

-   Junjie Li, School of Chinese Language and Literature, Nanjing Normal
    University, China

-   Zhixing Xu, School of Chinese Language and Literature, Nanjing
    Normal University, China

# Appendix: Selection of Resources

For more information about the EvaHan shared task and the ALP2025
workshop, visit the [official ALP2026
webpage](https://www.ancientnlp.com/alp2025/).

OCR Model

-   DeepSeek-OCR: <https://www.modelscope.cn/models/deepseek-ai/DeepSeek-OCR>

-   PaddleOCR-VL:
    <https://www.modelscope.cn/models/PaddlePaddle/PaddleOCR-VL>

-   mscoder/duguang-ocr-onnx-v2:
    https://www.modelscope.cn/models/mscoder/duguang-ocr-onnx-v2

-   RapidAI/RapidOCR: https://www.modelscope.cn/models/RapidAI/RapidOCR

-   iic/cv_convnextTiny_ocr-recognition-document_damo:
    https://www.modelscope.cn/models/iic/cv_convnextTiny_ocr-recognition-document_damo
