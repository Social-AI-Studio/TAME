# Zero Shot Multimodal Hateful Content Classification
**1. Introduction**
----------------------

The hateful meme is a particular form to express insulting information in social media platforms such as Facebook and Tweet using multimodel internet memes, which are defined by images overlaid with text. Detecting hateful memes is a difficult problem, as it often relies heavily on context, requires a very specific combination of information from different modalities (the text and the image). Sometimes it is easy for humans to detect, but challenging to AI models. It is also an significant problem to mitigate the side effect of hateful memes, as it has the potential to affect everyone in our society. However, there are varieties of abusive meanings in the world, the performance of machine learning approaches often suffer labeled data scarcity. To address those problems, we aim to integrate the hateful memes classification task into a zero-shot learning setting, where we trained the model to learn related knowledge from given hateful memes samples (from seen categories) and distinguish if the target hateful memes samples (from unseen categories) are hateful based on learned information.


**2. Contributions**
----------------------
Our main contributions are summarized as follows:

- To the best knowledge, we are the first paper to propose the task of zero-shot multimodal hateful content classification. 

- We proposed a novel model to address the zero-shot multimodal hateful content classification problem. We designed an attribute learning model to learn the auxiliary semantic information of hateful memes sample. Such specific knowledge will help the model to focus on category-level semantic instead of instance-level information, leading to learning the relationship between hateful and non-hateful information better.

- We re-splited the public FHM dataset based on a zero-shot learning setting and conducted extensive comprehensive experiments compare to the state-of-the-art. Our experiment results demonstrated that our model outperforms the related baseline model and can address the zero-shot multimodal hateful content classification problem effectively.


**3. Proposed Model**
----------------------
**3.1 Network Archetecture**


**4. Experiments**
----------------------
**4.1 Experimental Setup**

- Dataset: We conducted experiments on the Hateful Memes (HM) dataset compiled by Facebook AI. Based on zero shot learing setting, we re-splited the dataset and completed experiments in different unseen categories. The detailed information is shown blow. 

- Multimodel and semantic features: We use visualbert as the multimodel feature extractor, which is based on huggingface framework. For semantic features, excepting using sub-class labels, we also use an advanced image caption model to extract additional information of hateful memes. 

- Network architecture and hyper-parameter: 

- Baselines and Evaluation Metrics: We compared our model with three baseline models: visualbert, vilbert and lxmmert.

**4.2 Experimental Results**


**5. Timeline**
----------------------
Due Date: 11 Nov. 2021 (WWW2022)

week 1(10.2 - 10.8): 

- Doing some researches about feature fusion approaches and finishing a report

- Analysing the importance of cycle consistency loss (Ablation experiments), completing latest modification and getting corresponding results

- New framework diagram

week 2(10.9 - 10.15): Abstract ddl

week 3(10.16 - 10.22): Full paper ddl




