## 🔹 EMG for Hand/Finger Movements  

| Dataset Name | Source | Description | # of Subjects | # of Channels | Sampling Rate (Hz) | Electrode Placement | Data Format | Labels | License | Paper | Data Link |
|--------------|--------|-------------|---------------|---------------|--------------------|---------------------|-------------|--------|---------|-------|------|
| Multi-channel sEMG Hand Gesture Dataset | Mendeley Data | sEMG signals for 10 unique hand gestures | 40 | 4 | Not specified | Forearm muscles | csv,mat | Yes | CC BY 4.0 | [Paper](https://www.sciencedirect.com/science/article/pii/S2352340922001330?via%3Dihub) | [Dataset](https://data.mendeley.com/datasets/ckwc76xr2z/2) |

---

## 🔹 EMG for Prosthetics Control  

| Dataset Name | Source | Description | # of Subjects | # of Channels | Sampling Rate (Hz) | Electrode Placement | Data Format | Labels | Gesture Types | Prosthetic Type (if any) | Acquisition Protocol | Data Size | License | Paper | Data Link |
|--------------|--------|------------------|---------------|---------------|--------------------|---------------------|-------------|--------|----------------|---------------------------|----------------------|-----------|---------|--------|-----------|
| **Ninapro DB1** | Ninapro | First dataset with 52 movements from intact subjects using MyoBock electrodes | 27 | 10 sEMG + 8 acc. | 100 (EMG), 25 (acc.) | Forearm | .mat | Movement classes | 52 (hand, wrist, finger) | None | Visual cues | ~2.1 GB | CC BY-NC-SA 4.0 | [Atzori et al., 2014](https://www.nature.com/articles/sdata201410) | [DB1 Link](https://ninapro.hevs.ch/Database1) |
| **Ninapro DB2** | Ninapro | Similar to DB1 with 12 Otto Bock electrodes and higher sampling rate | 40 | 12 sEMG + 9 inertial | 2000 (EMG) | Forearm | .mat | Movement classes | 50 | None | Visual cues, rest positions | ~3.5 GB | CC BY-NC-SA 4.0 | Same as above | [DB2 Link](https://ninapro.hevs.ch/Database2) |
| **Ninapro DB3** | Ninapro | Trans-radial amputees performing DB2 protocol with prosthesis | 11 (amputees) | 12 sEMG + 9 inertial | 2000 | Residual limb | .mat | Movement classes | 50 | Trans-radial | Same as DB2 | ~1.2 GB | CC BY-NC-SA 4.0 | Same | [DB3 Link](https://ninapro.hevs.ch/Database3) |
| **Ninapro DB4** | Ninapro | Focuses on dynamics: includes force, torque, and acceleration | 10 | EMG + force sensors | 2000 | Forearm + fingers | .mat | Force + motion labels | 49 | None | Motion with force acquisition | ~2.8 GB | CC BY-NC-SA 4.0 | Same | [DB4 Link](https://ninapro.hevs.ch/Database4) |
| **Ninapro DB5** | Ninapro | Reduced gesture set for motor imagery task | 10 | 12 sEMG | 2000 | Forearm | .mat | Imagined movements | 18 | None | Visual cue-based | ~700 MB | CC BY-NC-SA 4.0 | Same | [DB5 Link](https://ninapro.hevs.ch/Database5) |
| **Ninapro DB6** | Ninapro | High-density EMG version of DB1 using Delsys Trigno sensors | 10 | HD-sEMG (up to 128) | 2000 | Forearm (grid) | .mat | Movement classes | 52 | None | Same as DB1 | ~5.1 GB | CC BY-NC-SA 4.0 | Same | [DB6 Link](https://ninapro.hevs.ch/Database6) |
| **Ninapro DB7** | Ninapro | EEG + EMG data from 2 amputees | 20 intacts, 2 amputees | 12 sEMG + EEG | 2000 (EMG), EEG variable | Scalp + residual limb | .mat | Movement classes | 50 | Trans-radial | EEG-EMG synchronous | ~900 MB | CC BY-NC-SA 4.0 | Same | [DB7 Link](https://ninapro.hevs.ch/Database7) |
| **Ninapro DB8** | Ninapro | Real-world use case with wireless sEMG sensors from amputees | 10 intacts, 2 amptuees | Wireless EMG (8+) | 2000 | Residual limb | .mat | Real-time motion | 52 | Trans-radial | Real-life scenario | ~1.6 GB | CC BY-NC-SA 4.0 | Same | [DB8 Link](https://ninapro.hevs.ch/Database8) |
| **Ninapro DB9** | Ninapro | Adds finger motion tracking with CyberGlove to EMG recordings | 77 | 12 sEMG + glove | 2000 (EMG), glove variable | Forearm + hand | .mat | Kinematic labels | 52 | None | Full hand tracking | ~2.9 GB | CC BY-NC-SA 4.0 | Same | [DB9 Link](https://ninapro.hevs.ch/Database9) |
| **Ninapro DB10** | Ninapro | Simultaneous bilateral movements from amputees and intact subjects | 30 intacts, 15 amputees | 12 sEMG each arm | 2000 | Forearm + residual limb | .mat | Mirrored movement classes | 52 | Trans-radial | Bilateral cue-based | ~1.3 GB | CC BY-NC-SA 4.0 | Same | [DB10 Link](https://ninapro.hevs.ch/Database10) |

