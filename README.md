# Quantum Information Processing - Applied Computer Science, AGH UST

Welcome to the Quantum Information Processing course offered in the 3rd semester of the 2nd year for Applied Computer Science at AGH University of Science and Technology, 2023 🎓👩‍🎓. This repository serves as your central resource for all course materials, including lectures, exercises, and lab sessions.

## Course Structure 🏛️

This course is designed to provide students with both theoretical and practical knowledge of quantum information processing. We will delve into the fundamental concepts of quantum mechanics and explore their applications in information processing, delving into the exciting world of quantum computing. 🌌

- **Lectures:** Gain a deep understanding of quantum mechanics and quantum computing principles.
- **Exercises:** Participate in engaging sessions to solve quantum-related problems.
- **Labs:** Implement and experiment with quantum algorithms using tools like IBM Quantum Experience.

## Prerequisites 📚

To fully engage with the lab assignments, please ensure you have the following prepared:
- Basic understanding of linear algebra and probability theory.
- Python 3.8 or higher.

## Setup 🛠️

1. Clone the repository to begin:
   ```bash
   git clone https://github.com/yourusername/quantum-information-processing-agh.git

2. Install necessary Python libraries:
   ```bash
   pip install qiskit numpy matplotlib

3. Sign up for an IBM Quantum Experience account for practical lab exercises.

## Common Commands 🛠️

Throughout the course, we will be using various commands for environment setup and management. Here are some of the commonly used commands:

### Conda Environment
```shell
conda create -n ibm_venv python=3.10.8
conda activate ibm_venv
conda info
conda env list 
activate ibm_venv
pip freeze
pip install -r requirements.txt
conda deactivate
conda env remove --name ibm_venv
```

### Virtual Environment
```shell
pip install virtualenv
python -m venv ibm_venv
.\ibm_venv\Scripts\activate
pip install -r requirements.txt
deactivate
```

### Docker Commands
```shell
docker build -t jupyter .
docker run -p 8888:8888 jupyter
jupyter server list
```