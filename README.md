Advanced Topics In Recommendation Systems - Final-Project:
Predicting Review Helpfulness within the P5 Framework


Historically, recommendation systems have necessitated the creation of unique architectures and training
methodologies tailored to specific tasks. This specialization often challenges the ability to leverage learned
knowledge and insights across different tasks, leading to a bottleneck in the generalization capabilities of these
systems. For example, a model adept at sequential recommendations might struggle to adapt to generating
reviews. Addressing this challenge, the “Pretrain, Personalized Prompt, and Predict Paradigm” (P5) emerged
as a versatile and unified approach utilizing the descriptive power of language to encapsulate and address a wide
array of recommendation tasks. In our work, we extend the P5 framework to include a new task: predicting
the helpfulness of user reviews. For example, a review considered helpful by 75% of users would receive a
helpfulness score of 0.75 on a scale from 1 to 5. This addition aims to enrich user experience by highlighting the
most valuable reviews, although our main ambition was to enhance the model’s multitasking capability rather
than maximizing its performance on this single metric. To this end, we developed varied prompts to probe
the new task from multiple perspectives and trained the model on a dataset covering both this and existing
tasks. This method leverages the Large Language Model (LLM) to perform diverse recommendation tasks by
integrating and applying insights broadly. Our comprehensive experiments and analyses on real-world data
underline the efficacy of this method and its contributions to the overarching goals of the P5 framework. Despite
the results not fully meeting our performance expectations, the focus of our project was to showcase the model’s
enhanced multitasking capabilities, rather than achieving peak performance in the new task alone.

Code: https://github.com/jeykigung/P5/tree/main
Paper: https://arxiv.org/pdf/2203.13366.pdf
