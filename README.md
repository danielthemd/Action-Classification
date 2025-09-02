Here is the previous README content in plain, normal font—no headings, bold, or markdown formatting:

Action Classification - Implementation

This project implements an action classification solution using a real-world wearable antenna dataset. It processes and analyzes signal and antenna parameters to identify activities such as jumping, sitting, standing, running, sleeping, and walking.

Project Structure:
- Action_Classification.ipynb: Main Jupyter notebook showing data import, exploration, and initial analysis.
- final_wearable_antenna_dataset_real_world.csv: Wearable antenna dataset with 5,000 samples and 35 feature columns.

Dataset Description:
The dataset records several signal and antenna attributes measured during different human activities. The primary columns are Activity, which is the target variable denoting the action performed (examples: jumping, running, sitting), and features including RSSI (dBm), SNR (dB), Path Loss (dB), Delay Spread (s), Angular Spread (degrees), Doppler Shift (Hz), Coherence Bandwidth (Hz), Antenna Position, Frequency (MHz), Material Used, Antenna Structure, Antenna Width, Length, Thickness, Relative Permittivity, Gain (dBi), SAR (W/kg), DGS Presence, Substrate Type, Feeding Type, Return Loss (dB), Bending Tolerance (degrees), Antenna Azimuth, Elevation, X, Y, Z Position, S11, S21 (dB), Theta, Phi, E-field (dB), H-field (dB).

How to Use:
1. Prepare your environment (Python 3.8+, pandas, scikit-learn, etc.) and place the dataset CSV in the working directory.
2. In the notebook: load the dataset using pandas, explore data with the .columns and .describe() functions, and prepare features and labels for model training.
3. Key operations include displaying columns and example records, and previewing statistics like mean, standard deviation, minimum, maximum, and quartiles for core features.

Data Statistics:
Rows: 5,000. Columns: 35.
Key stats include RSSI mean at -80.26 and standard deviation 12.92, with a minimum of -100 and maximum of -60. Angular spread mean is 180.32 degrees and maximum is 359.99 degrees. Azimuth, elevation, X, Y, Z positions range roughly from 0 to 180 and 0 to 50 units.

Usage Notes:
The notebook is ready for further feature engineering, visualization, and classification model training. The results and exploration steps can be expanded for any wearable signal learning task.
