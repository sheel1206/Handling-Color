# Overcoming-Color-Bias-through-Self-Supervision

Authors: Soumya Snigdha Kundu, Sheel Patel, Shaswat Srivatsava and Aarsh Chaube

Abstract: Self supervised models have recently shown to better supervised learning models in terms of accuracy scores. Another major advantage of utilising self supervised learning models is the power of learning appropriate representations and in-turn overcoming biases faced by supervised learning models. In this paper, we show that self supervised learning model over the the bias of color introduced to the task of digit recognition and maintain their ability to generalise through various values of variance and bias in the data. The model manages to exceed the accuracy of the supervised model by nearly 45%.

Primary Results: 
| Model | Data Variance | Accuracy (%) |
| :---         |     :---:      |          :---: |
| Proposed Self Supervised Network   | 0.05     | 95.2    |
| Proposed Self Supervised Network   | 0.02     | 95.3    |
| ResNet (Supervised)   | 0.05     | 61    |
| ResNet (Supervised)   | 0.02     | 50    |

Data:
1. MNIST - LeCun, Y. & Cortes, C. (2010). MNIST handwritten digit database.
2. Colored MNIST - Kim, B., Kim, H., Kim, K., Kim, S., & Kim, J. (2019). Learning not to learn: Training deep neural networks with biased data. In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (pp. 9012-9020).
