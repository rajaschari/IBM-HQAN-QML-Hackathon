# IBM-HQAN-QML-Hackathon

Team project submission for HQAN-sponsored IBM quantum hackathon. HQAN (http://hqan.illinois.edu) is the NSF Quantum Leap Challenge Institute. My awesome teammates(Yuchen Pang, Emily Waite and Aramide Moronfoye) and myself won joint-first place in the event(https://www.credly.com/badges/80f56d55-737b-4bce-861a-f0ad12a79c85/public_url).


## Brief summary of the problem:

The project tries to improve upon the score of the variational quantum amchine learning algorithm sugested in the paper: https://arxiv.org/abs/2007.14044.
We need to program a machine learning model which mojorly relies on variational quantum algorithms to solve a classification problem, importantly solving cases of multi-class classification. We use the Iris dataset as our test-bed since it is the simplest well-known non-binary dataset.

The code is self-explanatory with comments to help the logical flow of the design and changes made to the original model proposed in the paper.


## Results:

We achieved a final score of 0.97, which is 2% better than the model described in the paper. We use the model from the paper as our base case, and added improvements mainly focusing on:  
a) feature engineering. 
b) using a special loss function which penalized predictions in the subspace of the Hilbert space which is complementary to the code space.
