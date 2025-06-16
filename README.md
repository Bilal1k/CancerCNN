This project implements a lightweight convolutional neural network (CNN) to classify histopathologic images of lymph node tissue as cancerous or not, using the Kaggle "Histopathologic Cancer Detection" dataset. The model is built and trained using PyTorch, with a focus on fast experimentation and efficiency on limited hardware. To support rapid testing, hyperparameter tuning was performed on a 10% stratified sample.

The architecture, BasicCNN, is intentionally small to accommodate Kaggle’s free GPU environment while still capturing relevant visual features in 96×96 image tiles. The pipeline includes custom dataset loading, training loop with mixed-precision AMP, metric tracking, and visualization. This project highlights the importance of efficient model design and code optimization when working with CNNs under compute constraints.

This project was created as part of an assignment for CNNs for DTSA 5511 in the Data Science MS from the university of Boulder Colorado
