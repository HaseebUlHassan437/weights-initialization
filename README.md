# weights-initializationWeight Initialization in Neural Networks
This repository demonstrates the impact of different weight initialization strategies in training deep neural networks. Through practical notebooks, we explore how zero initialization can cause training failure and how appropriate initialization methods resolve it — especially with ReLU and Sigmoid activations.

📁 Files Included
File	Description
Copy_of_zero_initialization_relu.ipynb	Shows how zero initialization fails when used with ReLU activation. The network does not learn due to zero gradients.
zero_initialization_sigmoid.ipynb	Demonstrates vanishing gradients issue caused by zero initialization in Sigmoid-based neural networks.
weights_initialization_problem_solved.ipynb	Implements He/Xavier initialization, which overcomes the issues and allows proper model convergence.

🧠 Key Concepts
Zero Initialization Pitfall: All neurons start with the same weights, leading to no diversity in learning.

Vanishing Gradients: Especially with sigmoid activations, improper initialization causes gradients to vanish, halting learning.

Proper Initialization Fix:

Xavier Initialization: For sigmoid/tanh activations.

He Initialization: For ReLU/Leaky ReLU activations.

🛠️ Requirements
Python 3.x

Google Colab / Jupyter Notebook

Libraries:

numpy

matplotlib

tensorflow or keras

Install with:

bash
Copy
Edit
pip install numpy matplotlib tensorflow
✅ How to Run
Clone the repository:

bash
Copy
Edit
git clone https://github.com/HaseebUlHassan437/weights-initialization.git
cd weights-initialization
Open the notebooks in Google Colab or Jupyter Notebook.

Run each notebook step by step to observe training behavior under different initialization strategies.

🎓 Learning Outcomes
Understand why initial weights matter in training.

Learn the failure cases of zero initialization.

Observe the improvements with He/Xavier initialization in convergence speed and accuracy.

👨‍💻 Author
Haseeb Ul Hassan
GitHub: @HaseebUlHassan437

📜 License
This project is licensed under the MIT License — use it freely for learning or teaching.
