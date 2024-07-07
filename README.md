As part of a natural language processing course project, we tackled iSarcasmEval task at SemEval 2022, which focused on detecting intended sarcasm in English. Sarcasm detection is a critical area in NLP due to its disruptive effect on computational systems used for tasks such as sentiment analysis, opinion mining, and harassment detection.

Task Overview:
Motivation and Background: Sarcasm, a form of verbal irony, presents a significant challenge for computational systems because of the discrepancy between the literal and intended meanings of utterances. This task aimed to improve sarcasm detection, addressing issues in previous methods that relied on noisy or subjective labels.

Data Collection: The sarcasm labels were provided directly by the authors of the texts. This method aimed to eliminate the inaccuracies associated with proxy labelling methods such as hashtags or third-party annotators. The datasets compiled for this task included:

English Texts: Each text was labelled as sarcastic or non-sarcastic by its author.
Rephrased Texts: Authors provided non-sarcastic rephrasings of their sarcastic texts to convey the same meaning without sarcasm.

Sub-Tasks:
SubTask A: Participants were required to determine whether a given text was sarcastic or non-sarcastic.
SubTask C: Given a pair of texts—a sarcastic text and its non-sarcastic rephrase—participants needed to identify which text was the sarcastic one.

Evaluation Metrics: The task used precision, recall, accuracy, and macro-F1 as evaluation metrics. The primary metrics for evaluation were the F1-score for the sarcastic class in SubTask A, the Macro-F1 score for SubTask B, and accuracy for SubTask C.

The task provided a comprehensive understanding of the complexities involved in sarcasm detection, highlighting the linguistic nuances that can vary significantly. It not only deepened our technical skills in NLP but also underscored the importance of accurate and reliable data annotation methods in improving the performance of sarcasm detection models.

Models hosted at the following google drive link: https://drive.google.com/drive/folders/1i57GnQ8Q2izMdpI-t4RgHhj1Pv1CCHT2?usp=sharing
