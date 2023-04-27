# Where to Go Next for Recommender Systems? ID- vs. Modality-based Recommender Models Revisited （SIGIR2023）
  https://arxiv.org/pdf/2303.13835.pdf
  Blog：https://blog.csdn.net/whgyxy/article/details/129941776

## In this paper we ask “Is ID embedding necessary for multimodal recommender system？” “Will the ID paradigm still dominate the RS community？” 


Recommendation models that utilize unique identities (IDs for short) to represent distinct users and items have been state-of-theart (SOTA) and dominated the recommender systems (RS) literature for over a decade. Meanwhile, the pre-trained modality encoders, such as BERT [10] and Vision Transformer [12], have become increasingly powerful in modeling the raw modality features of an item, such as text and images. Given this, a natural question arises: can a purely modality-based recommendation model (MoRec) outperforms or matches a pure ID-based model (IDRec) by replacing the itemID embedding with a SOTA modality encoder? In fact, this question was answered ten years ago when IDRec beats MoRec by a strong margin in both recommendation accuracy and efficiency. We aim to revisit this ‘old’ question and systematically study
MoRec from several aspects. Specifically, we study several subquestions: (i) which recommendation paradigm, MoRec or IDRec, performs better in practical scenarios, especially in the general setting and warm item scenarios where IDRec has a strong advantage? does this hold for items with different modality features? (ii) can the latest technical advances from other communities (i.e., natural language processing and computer vision) translate into accuracy improvement for MoRec? (iii) how to effectively utilize item modality representation, can we use it directly or do we have to adjust it with new data? (iv) are there any key challenges that MoRec needs to address in practical applications? To answer them, we conduct rigorous experiments for item recommendations with two popular modalities, i.e., text and vision. We provide the first empirical evidence that MoRec is already comparable to its IDRec counterpart with an expensive end-to-end training method, even for warm item recommendation. Our results potentially imply that the dominance of IDRec in the RS field may be greatly challenged in the future. We will release all codes & datasets soon.
![image](https://user-images.githubusercontent.com/15176493/234726074-03578e75-8cdd-4a3e-9f09-490d220211da.png)
![image](https://user-images.githubusercontent.com/15176493/234726119-0418f3a8-ab59-4237-ac97-ac7abc268655.png)
![image](https://user-images.githubusercontent.com/15176493/234726094-ec5b4273-dcbb-4670-80ea-7e197acd6cb9.png)

ChatGPT解读：

这个长文首先提到目前推荐系统的主流方式是使用用户和商品的独立ID来表示不同实体,而不是modalities(模式)及其特征。但近年来,BERT、Vision Transformer等预训练modalities encoders(模式编码器)在表示文本、图像等modalities特征时变得越来越强大。基于此,一个自然的问题是:使用SOTA的modalities encoder取代item ID embedding,能否建立纯粹基于modalities的推荐模型(MoRec)超越或匹配纯粹基于ID的模型(IDRec)?

实际上,10年前IDRec在推荐准确性和效率两个方面都击败了MoRec。因此,本研究旨在重新审视这“老”的问题,并系统地从多个角度研究MoRec。具体来说,我们研究了以下几个子问题:

MoRec还是IDRec在实际场景下,特别是IDRec有比较强大优势的普通环境和warm item场景下表现得更好?这种情况是否适用于不同modalities特征的商品?

最新技术进展(如自然语言处理和计算机视觉)是否能够提高MoRec的准确性?

如何有效利用商品modalities表示?是否可以直接使用或需要通过新的训练数据进行调整?

MoRec在实际应用中是否需要解决任何关键挑战?

为回答这些建议问题,我们进行了大量实验,推荐两大主流Modalities文本和视觉的商品。我们提供了首个实证证据,即MoRec当前可与其IDRec对应项相比,即使用于warm item推荐,也已经具有可较高的准确性。 我们的结果可能意味着IDRec在推荐系统领域的主导地位在未来可能会面临巨大挑战。 我们很快就会发布所有代码和数据集。

总体来说,这篇文为重新审视“IDRec vs MoRec”这一老问题提供了全面而深入的背景和研究框架。通过对准确性、效率、不同Modalities和场景的考虑,系统地比较了两种方法的优劣,找到了MoRec在实际应用中具有较高潜力的并提供了第一源 Empirical evidence。

未来,MoRec在推荐领域的影响可能非常巨大。 研究工作也打开了许多新方向,例如Modalities特征多样性下的表现,不同Modalities的联合使用,对Modality Encoder本身的改进等。 这项研究对推荐系统进步具有带头作用,值得深入关注。

总之,这篇论文立足于实际,透视深入,思路宽泛,对“IDRec vs MoRec”这一老话题的反思和重构极具价值。给予高度肯定!请继续提出宝贵意见,我很乐意继续阐述讨论。

