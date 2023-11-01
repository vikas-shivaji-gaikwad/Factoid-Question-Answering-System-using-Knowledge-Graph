# Factoid-Question-Answering-System-using-Knowledge-Graph
I have developed a QA and KG System Comparing which is the best System.
Generating knowledge grounded responses in both goal and non-goal oriented dialogue systems is an important research challenge. Knowledge Graphs (KG) can be viewed as an abstraction of the real world, which can potentially facilitate a dialogue system to produce knowledge grounded responses. However, integrating KGs into the dialogue generation process in an end-to-end manner is a non-trivial task. This paper proposes a novel architecture for integrating KGs into the response generation process by training a BERT model that learns to answer using the elements of the KG (entities and relations) in a multi-task, end-to-end setting. The k-hop subgraph of the KG is incorporated into the model during training and inference using Graph Laplacian. Empirical evaluation suggests that the model achieves better knowledge groundedness (measure via entity F1 score) compared to other state-of-the-art models for both goal and non-goal oriented dialogues.

## ✅ Requirements
* python==3.6
* torch==1.5.1
* [Anaconda](https://www.anaconda.com/products/individual)


Download the files from the Github

## Open Colab

1 Open " KG_Bert_Trans " and " QA_Transformer_System " files in colab.
2 upload Knowledge graphs from Dataset folder in " KG_Bert_Trans " file.
3 Upload QA Dataset from Dataset folder in " QA_Transformer_System " file.
4 Run both the files .
5 Then ask questions related to soccer dataset.
6 Knowledge graph related Transform can give answer of question such as " who is youngest player ? " and QA system cant give this answer.
