# Fusion-Power-Prediction-using-PINNs

Developed and compared advanced machine learning models (including a PINN and a standard Neural Network) to efficiently predict the power output of nuclear fusion reactors, aiming to replace computationally expensive traditional simulations.

Key Innovation: Architected a Physics-Informed Neural Network (PINN) that uses a custom physics loss function to enforce the steady-state fusion power law and the Boche-Hale Reactivity Curve, ensuring physically consistent predictions.

Methodology: Preprocessed and normalized a complex dataset of over 10,000 experimental runs, employing careful scaling to handle extreme physical values and prevent numerical overflow.

Results: Successfully trained the models and evaluated them based on errors, demonstrating the PINN's ability to provide efficient and physically grounded predictions.
