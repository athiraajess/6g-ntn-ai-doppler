# AI-Based Doppler Estimation for 6G NTN Links

This project explores AI-assisted Doppler frequency estimation for
non-terrestrial networks (NTN), motivated by high-mobility LEO satellite
communications in future 6G systems.

## Motivation
In NTN scenarios, high relative velocity causes significant Doppler
shifts that degrade synchronization and detection performance.
Classical estimation methods may struggle under low SNR or non-ideal
conditions.

## Approach
- Simulated a baseband communication system with Doppler impairment
- Implemented a classical Doppler estimator as baseline
- Trained a small neural network to estimate Doppler shift from received signals
- Compared estimation accuracy under varying SNR and Doppler conditions

## Tools
- Python
- NumPy, SciPy
- PyTorch (for neural network)
- MATLAB-style signal modeling

## Key Observations
AI-based estimation showed improved robustness under noisy and
time-varying conditions, while classical estimators remain efficient
under ideal assumptions.

This project is intended as a small-scale exploratory study rather than
a production-level system.
