# Zero Shot Multimodal Hateful Content Classification
> **1. Introduction**

The hateful meme is a particular form to express insulting information in social media platforms such as Facebook and Tweet using multimodel internet memes, which are defined by images overlaid with text. Detecting hateful memes is a difficult problem, as it often relies heavily on context, requires a very specific combination of information from different modalities (the text and the image). Sometimes it is easy for humans
to detect, but challenging to AI models. It is also an significant problem to mitigate the side effect of hateful memes, as it has the potential to affect everyone in our society. However, there are varieties of abusive meanings in the world, the performance of machine learning approaches often suffer labeled data scarcity. To address those problems, we aim to integrate the hateful memes classification task into a zero-shot learning setting, where we trained the model to learn related knowledge from given hateful memes samples (from seen categories) and distinguish if the target hateful memes samples (from unseen categories) are hateful based on learned information.


> **2. Contributions**

Our main contributions are summarized as follows:

- To the best knowledge, we are the first paper to propose the task of zero-shot multimodal hateful content classification. We proposed a novel model to address the zero-shot multimodal hateful content classification problem. we designed a VAE-GAN model and use the specific class labels as auxiliary semantic information, which help to learn the relationship between specific hateful and non-hateful information.

- We re-splited the public FHM dataset based on a zero-shot learning setting and conducted extensive comprehensive experiments compare to the state-of-the-art. Our experiment results demonstrated that our model outperforms the related baseline model and can address the zero-shot multimodal hateful content classification problem effectively.


> **3. Proposed Model**

3.1 Problem Task Definition

3.2 Network Archetecture

![Image text](https://gitlab.com/dianachu1026/img/-/raw/main/model.jpg)


>** 4. Experiments**

4.1 Experimental Setup

Dataset: We conducted experiments on the Hateful Memes (HM) dataset compiled by Facebook AI. Based on zero shot learing setting, we re-splited the dataset and completed experiments in different unseen categories. The detailed information is shown blow. 

![Image text](https://gitlab.com/dianachu1026/img/-/raw/main/dataset.jpg)


4.2 Experimental Results

![Image text](https://gitlab.com/dianachu1026/img/-/raw/main/visualbert.jpg)


> **5. Timeline**

Due Date: 11 Oct 2021 (WWW2022)

week 1(9.10-9.16): Get the results of proposed model and supplementary experiments.
week 2(9.17-9.23): Experiments and paper writing
week 3(9.24-9.30): Experiments and paper writing
week 4(10.1-10.7): Experiments and paper writing




