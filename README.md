# IDforRec

# Where to Go Next for Recommender Systems? ID- vs. Modality-based Recommender Models Revisited

In this paper we ask “Is ID embedding necessary for multimodal recommender system？” “Will the ID paradigm still dominate the RS community？”


Recommendation models that utilize unique identities (IDs for short) to represent distinct users and items have been state-of-theart (SOTA) and dominated the recommender systems (RS) literature for over a decade. Meanwhile, the pre-trained modality encoders, such as BERT [10] and Vision Transformer [12], have become increasingly powerful in modeling the raw modality features of an item, such as text and images. Given this, a natural question arises: can a purely modality-based recommendation model (MoRec) outperforms or matches a pure ID-based model (IDRec) by replacing the itemID embedding with a SOTA modality encoder? In fact, this question was answered ten years ago when IDRec beats MoRec by a strong margin in both recommendation accuracy and efficiency. We aim to revisit this ‘old’ question and systematically study
MoRec from several aspects. Specifically, we study several subquestions: (i) which recommendation paradigm, MoRec or IDRec, performs better in practical scenarios, especially in the general setting and warm item scenarios where IDRec has a strong advantage? does this hold for items with different modality features? (ii) can the latest technical advances from other communities (i.e., natural language processing and computer vision) translate into accuracy improvement for MoRec? (iii) how to effectively utilize item modality representation, can we use it directly or do we have to adjust it with new data? (iv) are there any key challenges that MoRec needs to address in practical applications? To answer them, we conduct rigorous experiments for item recommendations with two popular modalities, i.e., text and vision. We provide the first empirical evidence that MoRec is already comparable to its IDRec counterpart with an expensive end-to-end training method, even for warm item recommendation. Our results potentially imply that the dominance of IDRec in the RS field may be greatly challenged in the future. We will release all codes & datasets soon.
![image](https://user-images.githubusercontent.com/15176493/234726074-03578e75-8cdd-4a3e-9f09-490d220211da.png)
![image](https://user-images.githubusercontent.com/15176493/234726119-0418f3a8-ab59-4237-ac97-ac7abc268655.png)
![image](https://user-images.githubusercontent.com/15176493/234726094-ec5b4273-dcbb-4670-80ea-7e197acd6cb9.png)

