# DAB-PYNB
## 📘 **DAB Python Notebooks**

This repository contains a small collection of **Jupyter notebooks** demonstrating how to programmatically access **DAB (Discovery and Access Broker)** services using the **`dab-py` Python library**.

The notebooks focus on accessing:
- **WHOS (WMO Hydrological Observing System)**
- **HIS-Central**

via the **OGC OM-JSON API**, showing how to discover features, retrieve observations, and download data programmatically.

## 📂 Repository contents
| Notebook | Description |
|--------|-------------|
| `dab_py_demo_his_central.ipynb` | Tutorial on accessing HIS-Central data using `HISCentralClient` |
| `dab_py_demo_whos.ipynb` | Tutorial on accessing WHOS data using `WHOSClient` |

Each notebook is self-contained and includes:
- Client initialization with API tokens
- Feature discovery and filtering
- Observation retrieval
- Optional pagination
- Conversion to `pandas` DataFrames
- Basic time-series plotting
- Optional data download workflow (for HIS-Central)

## 🚀 Open in Google Colab
All notebooks can be executed directly in **Google Colab**, which means:
- No local installation required
- Interactive execution in your browser
- Easy testing and learning
Click the badges in each notebook to open them in Colab.

## 🐍 Prerequisites
These notebooks rely on the **`dab-py`** Python package.
If running locally:
```bash
pip install dab-py
```
Or inside a notebook:
```bash
!pip install --upgrade dab-py
```
Note: It’s recommended to keep dab-py up-to-date to ensure compatibility with the latest DAB services.

## 🔑 Authentication
Access to WHOS and HIS-Central requires a valid API token.
Tokens are issued after registration with the relevant DAB service providers.

## 🔗 Related repositories
dab-py (Python client library)
https://github.com/ESSI-Lab/dab-py