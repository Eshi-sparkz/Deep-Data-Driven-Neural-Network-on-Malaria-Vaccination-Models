Deep Data-Driven Neural Network for Malaria Vaccination

This repository contains the research, mathematical models, and simulation code supporting the paper
“Deep Data-Driven Neural Network for Malaria Vaccination” by Esi Abaka-Quansah and Stephen E. Moore (2025).

🧠 Overview

Malaria continues to be a major global health issue, particularly in Sub-Saharan Africa. This research develops a deep, data-driven mathematical model that integrates epidemiological modeling and machine learning to predict and optimize malaria vaccination outcomes, focusing on the RTS,S/AS01 malaria vaccine program in Ghana.

📊 Key Features

Mathematical Modeling:
Formulation of a compartmental vaccination model (Susceptible, Infected, Recovered, Vaccinated) using differential equations.

Epidemiological Analysis:

Disease-Free and Endemic Equilibrium Analysis

Reproductive number (R₀) computation

Stability and sensitivity analysis using Partial Rank Correlation Coefficients (PRCC)

Deep Learning Integration:

Neural networks used to learn and predict vaccination dynamics

Models include ResNet, LSTM, GRU, BiLSTM, and hybrid variants (such as ResNet-LSTM and ResNet-GRU).

Implemented using TensorFlow and Keras

Simulation Insights:

Python-based simulations visualize malaria spread under varying vaccination rates and efficacies

Results demonstrate that maintaining high vaccine efficacy and consistent coverage can reduce infection rates below eradication thresholds (R₀ < 1)

⚙️ Methods

Generate synthetic malaria vaccination datasets reflecting Ghana’s population dynamics.

Train deep neural networks using k-fold cross-validation for parameter learning.

Integrate learned parameters into the epidemiological ODE model.

Simulate malaria spread and vaccination impact under multiple scenarios.

🧩 Results

BiLSTM achieved the lowest prediction error (RMSE and MAPE) among recurrent models.

ResNet-GRU hybrid provided the most accurate overall forecasting performance.

The model demonstrates that malaria elimination is achievable with high vaccination coverage and improved vaccine efficacy.

🧮 Tools & Libraries

Python 3.x

TensorFlow / Keras

NumPy / Pandas / Matplotlib

SciPy (ODE Solvers)

📘 Citation

If you use this work, please cite:

Abaka-Quansah, E., & Moore, S. E. (2025). Deep Data-Driven Neural Network for Malaria Vaccination. Preprint. DOI: 10.21203/rs.3.rs-5789145/v1

📄 License

This research is distributed under the Creative Commons Attribution 4.0 International License (CC BY 4.0).
