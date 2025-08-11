# EEG-data-for-Mental-Arithmetic-Task
EEG Data acquired from g-tech UNICORN Blondy Black 8-channel headset
EEG data were acquired using the g.tec UNICORN Blondy Black 8-channel headset. Recordings were taken from eight scalp locations — Fz, C3, Cz, C4, Pz, PO7, Oz, and PO8 — while the device’s two conventional wet electrodes (A1 and A2) served as mastoid references. The headset features ten electrodes in total, with eight dry comb electrodes embedded in a free-size cap and the two wet reference electrodes positioned at the mastoids.

All participants provided informed consent prior to data collection. Recordings took place in a quiet laboratory setting under normal lighting conditions. The acquisition parameters included a 0.5–40 Hz band-pass filter, a 50 Hz notch filter, and an amplitude range of 0–100 µV to minimise artifacts. Data were sampled at 24-bit resolution and 250 Hz per channel.

EEG signals were captured and visualised using the UNICORN Suite Hybrid Black software via Bluetooth connectivity. Data were stored in CSV format for offline analysis and processing. For each participant, separate sessions were recorded for baseline, 3-digit serial subtraction, and 3-digit serial addition tasks, with verbal “start” and “stop” cues marking the beginning and end of each session.

The EEG data were preprocessed to remove EMG, EOG, and outlier artifacts using Independent Component Analysis (ICA). The resulting cleaned data were saved in .npz format and are available here.
