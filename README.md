# FL-XGBoost: Focal-Loss-Modified XGBoost for Network Intrusion Detection

## Overview
This repository contains the code fro FL-XGBoost, a modified XGBoost model 
that replaces the standard log-loss with a focal loss function (γ=2) to 
improve detection of rare network attacks in imbalanced traffic datasets.

## Setup
'''bash
pip install -r requirements.txt
'''

##Dataset 
-Public: CICIDS2017 - https://www.unb.ca/cic/datasets/ids-2017.html
- Primary: KNUST campus network logs (to be collected under HSSEC ethics clearance)

##Reproducibility
All experiments use random_state=42. See notebooks/ folder for training scripts

##Author
Abiagil Boateng | KNUST | 2026
