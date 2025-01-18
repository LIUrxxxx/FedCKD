# FedCKD
Currently, many smart IoT services and applications are emerging, and federated learning has emerged to train global models by effectively leveraging the large amount of user-generated data on IoT devices. However, in practical applications, the training data across different user terminals are often non-iid. When the data distribution among user terminals is very different, the performance of the model will be greatly reduced if the knowledge learned from other user terminals is directly obtained. Furthermore, federated learning does not offer robust privacy protection, posing a privacy leakage risk during parameter uploading. To address these issues, we propose FedCKD, a trusted personalized federated learning method based on clustering and knowledge distillation. Considering the negative impact of mitigating the non-iid data, a personalized model is obtained for each client through clustering and knowledge distillation. Firstly, a K-means clustering algorithm based on Canopy is used. Then, it uses cyclic knowledge distillation to extract common knowledge, and performes re-learning to achieve personalization. Our approach also implements privacy protection using a distributed differential privacy mechanism based on a shuffling algorithm. Extensive experiments show that FedCKD performs significantly better than state-of-the-art baselines.
