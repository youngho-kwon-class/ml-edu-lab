# 🧠 AdamP vs Adam Optimizer Benchmark

This project compares the performance of two popular deep learning optimizers—**Adam** and **AdamP**—across two benchmark datasets: **FashionMNIST** and **CIFAR-10**.  
The goal is to evaluate:

- ⚡ Training efficiency  
- 📉 Convergence speed  
- 🎯 Final accuracy  

---

## 📁 Project Structure

| Folder         | Description                                                                 |
|----------------|-----------------------------------------------------------------------------|
| `cifar10/`      | Code and notebooks for benchmarking Adam vs AdamP on the CIFAR-10 dataset |
| `fashionmnist/` | Code and notebooks for benchmarking Adam vs AdamP on the FashionMNIST dataset |

---

## 💡 Optimizer Concepts

- **Adam (Adaptive Moment Estimation)**  
  Combines Momentum and RMSprop. It adapts learning rates for each parameter using estimates of first and second moments of gradients. Known for fast convergence and robustness.

- **AdamP (Adam with Projection)**  
  Enhances Adam by introducing a projection step that helps avoid poor generalization caused by over-adaptive updates. Especially useful in vision tasks and models with large parameter spaces.

---

## 📓 Open Notebooks in Google Colab

Launch the notebooks directly in Google Colab:

- **CIFAR-10 Benchmark**  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/youngho-kwon-class/ml-edu-lab/blob/main/adamp-vs-adam-benchmark/cifar10/adam-benchmark-cifar10.ipynb)

- **FashionMNIST Benchmark**  
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/youngho-kwon-class/ml-edu-lab/main/adamp-vs-adam-benchmark/fashionmnist/adam-benchmark-fashionmnist.ipynb)


---

## 📊 Potential Extensions

Want to take this further? Consider adding:

- 📈 Visualizations of loss and accuracy curves for both optimizers  
- 🧪 Tests on additional datasets like SVHN or TinyImageNet  
- 🧠 Integration with different model architectures (e.g., ResNet, EfficientNet)

---
