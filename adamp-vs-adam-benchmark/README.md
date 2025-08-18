AdamP vs Adam Optimizer Benchmark ✨
This project was created to compare the performance of two widely-used optimization algorithms in deep learning: Adam and AdamP. It benchmarks training efficiency, convergence speed, and final accuracy using the FashionMNIST and CIFAR-10 datasets.

📂 Project Structure
.
├── cifar10/
│   └── cifar10_benchmark.ipynb
├── fashionmnist/
│   └── fashionmnist_benchmark.ipynb
└── README.md
cifar10/: Contains the code to compare the performance of Adam and AdamP on the CIFAR-10 dataset.

fashionmnist/: Contains the code to compare the performance of Adam and AdamP on the FashionMNIST dataset.

💡 Key Concepts
Adam (Adaptive Moment Estimation): A highly efficient and widely-used optimization algorithm that combines the advantages of Momentum and RMSprop, dynamically adjusting the learning rate for each parameter during training.

AdamP (Adam with Projection): A variant of Adam that introduces a "projection" concept to the weight update rule. It aims to improve convergence speed and the model's generalization performance.

🚀 How to Run the Code

Navigate to either the cifar10/ or fashionmnist/ folder.

Open the .ipynb file in Google Colab.

Execute the cells in order as instructed within the notebook.
