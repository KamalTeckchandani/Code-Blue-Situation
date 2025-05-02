**Cardiac Arrest Prediction – Code Blue Situation**

An AI-Based Predictive Model for Early Detection of Cardiac Arrest Events

🧠 **Overview**

The Code Blue Situation project is an AI-driven predictive system designed to anticipate cardiac arrest events by analyzing patient records, including ECG measurements and vital signs. The model aims to enable early interventions, optimize resource utilization in hospitals, and ultimately improve survival rates in emergency scenarios.

This system surpasses traditional methods like the Modified Early Warning Score (MEWS) by offering better accuracy using machine learning techniques, primarily focusing on Neural Networks, K-Nearest Neighbors (KNN), and Keras-based Deep Learning Models.

🚀 **Key Features**

🏥 Cardiac Arrest Prediction: Early prediction of cardiac arrest using real-time and historical data.

🔍 Multi-Class Classification: Classifies patients into 13 different heart condition categories based on ECG signals.

🧠 Machine Learning Models:

Neural Networks (Custom TensorFlow/Keras implementation)

K-Nearest Neighbors

Comparative studies with Naive Bayes, SVM, Random Forest

📈 **Accuracy Improvement:** Achieved up to 76% accuracy using Neural Networks with Leaky-ReLU activation.

📂 Project Structure
.
├── data/
│   ├── reduced_features.csv
│   └── target_output.csv
├── models/
│   ├── neural_network_tf.py
│   ├── neural_network_keras.py
│   ├── knn_classifier.py
├── results/
│   └── performance_analysis.png
├── README.md
├── requirements.txt
└── presentation/
    └── BE Blackbook.pdf

📊 **Dataset**

Total Attributes: 279 features (206 continuous, rest nominal)

Data Sources:

Demographic data

ECG measurements (12-lead)

Heart rate, QRS interval, P-R interval, etc.

Post Feature Selection: Reduced to 175 key attributes for efficient training and prediction.

🏗️ **System Design**

Iterative Development Model: Rapid prototyping with repeated refinement.

Modular Structure: Preprocessing → Model Training → Prediction → Evaluation.

Data Flow: Raw Data → Feature Selection → Model Training → Output Prediction.

Visuals include DFDs (Level 0, 1, 2), State Diagrams, Conceptual Design, and Gantt Charts for development planning.

⚙️ **Technologies Used**

Programming Language: Python 3.5+

Libraries:

TensorFlow

Keras

Scikit-learn

Pandas, NumPy, Matplotlib

Tools:

Jupyter Notebook

Anaconda

📈 **Result Highlights**

Best Model: Neural Networks (Keras)

Achieved Accuracy: 76%

Comparative Performance:

Naive Bayes: 47%

SVM: 63%

Random Forest: 65%

KNN: 54%

🧪 **Testing Strategy**

Unit Testing: Each model module

Integration Testing: End-to-end prediction flows

GUI Testing: For the web-based prediction interface

Optimization Experiments:

Varying batch sizes

Changing number of hidden layers

Different learning rates

📌 **Future Scope**

Integration with real-time ECG monitoring devices.

Expansion to behavioral and family history datasets.

Enhancing prediction accuracy with ensemble methods.

Deployable mobile or cloud-based predictive platforms for rural areas.

📬 **Contact If you like the project or want to collaborate, feel free to connect:**

GitHub: (https://github.com/KamalTeckchandani)

LinkedIn: https://www.linkedin.com/in/kamal-teckchandani/
