# Datasets

Raw dataset files are **not** included in this repository due to their size
(~850 MB combined). To reproduce the notebook, download the datasets below and
place the listed files directly in this `data/` directory (the notebook reads
them by filename from the working directory).

## 1. CICIDS2017

- **Source:** Canadian Institute for Cybersecurity, University of New
  Brunswick — [https://www.unb.ca/cic/datasets/ids-2017.html](https://www.unb.ca/cic/datasets/ids-2017.html)
  (also mirrored on Kaggle as `chethuhn/network-intrusion-dataset`)
- **Files expected** (CSV, one per capture day/session):
  - `Monday-WorkingHours.pcap_ISCX.csv`
  - `Tuesday-WorkingHours.pcap_ISCX.csv`
  - `Wednesday-workingHours.pcap_ISCX.csv`
  - `Thursday-WorkingHours-Morning-WebAttacks.pcap_ISCX.csv`
  - `Thursday-WorkingHours-Afternoon-Infilteration.pcap_ISCX.csv`
  - `Friday-WorkingHours-Morning.pcap_ISCX.csv`
  - `Friday-WorkingHours-Afternoon-PortScan.pcap_ISCX.csv`
  - `Friday-WorkingHours-Afternoon-DDos.pcap_ISCX.csv`

## 2. NSL-KDD

- **Source:** Canadian Institute for Cybersecurity — [https://www.unb.ca/cic/datasets/nsl.html](https://www.unb.ca/cic/datasets/nsl.html)
- **File expected:** `KDDTrain+.txt`

## 3. UNSW-NB15

- **Source:** Australian Centre for Cyber Security (ACCS), UNSW Canberra —
  [https://research.unsw.edu.au/projects/unsw-nb15-dataset](https://research.unsw.edu.au/projects/unsw-nb15-dataset)
- **File expected:** `UNSW_NB15_training-set.parquet`
  (the official release ships CSV; the parquet file used here is a direct
  format conversion of the same training-set split, no rows/columns changed)

## Notes

- These datasets are publicly released by their respective research groups for
  academic use. This repository does not claim ownership of any dataset and
  redistributes none of the raw data.
- Refer to each source's own license/usage terms before downloading.
