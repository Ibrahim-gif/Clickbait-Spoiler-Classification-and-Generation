# Clickbait-Spoiler-Classification-and-Generation
The project aims at generating short texts that satisfy the curiosity induced by a clickbait post.

Clickbait is a tactic used in online content, like headlines and social media posts, that aims to lure users into clicking or engaging with the material by using sensational or misleading information to create curiosity. While it can increase website traffic and ad revenue, it's often criticized for not delivering on its promises, which can harm trust and credibility in online sources. Finding the right balance between attracting engagement and delivering valuable content is crucial for content creators and platforms to maintain user satisfaction and authenticity in the digital realm.

The first task contains classification and the second task is spoiler generation 
In the first task, RoBERTa(Liu et al., 2019),DistillBert(Sanh et al., 2020) and DeBERT(He et al.,
2021) models were utilized for classification to determine the type of spoiler (i.e., "phrase," "passage,"
or "multi"). The evaluation of the classification models was based on accuracy and F1 score
metrics, providing insights into the overall correctness and balanced performance of the models
in accurately classifying the various spoiler types.

In the second task, SQuAD analysis was conducted using pre-trained models, namely BERT-base(bert-base-uncased-squad v1, 2019), DeBERTa-v3-base-squad2(deberta-v3-base squad2, 2022), and RoBERTa-base-SQuAD2(base squad2, 2022). These models have undergone pre-training specifically for question answering tasks on the SQuAD dataset. The main objective is to generate spoilers for clickbait posts and
evaluate the quality of the generated spoilers.