# CASPER: Context-Aware IoT Anomaly Detection System for Industrial Robotic Arms

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Last Commit](https://img.shields.io/github/last-commit/yourusername/yourrepository)
![Issues](https://img.shields.io/github/issues/yourusername/yourrepository)

Welcome to the repository for the paper titled **CASPER**. This system is designed for anomaly detection in industrial robotic arms using IoT technology. 

## Main Jupyter Notebook
The main analysis and presentation of our work can be found in the Jupyter notebook:
- [`casper.ipynb`](/notebooks/casper.ipynb)

Check the first cell for more information and also to access the datasets.

## Node-RED BLE Communication Package
Explore our [Node-RED package](https://github.com/hkayann/node-red-contrib-ble-sense) designed to enable BLE communication at the edge.

## Arduino Sketch for BLE IMU Data
Check out the `niclaBLEIMUStruct` folder in the above repository for the Arduino sketch used in our research.

## Reference
If you use CASPER in your research, please cite our paper:
```bibtex
@article{10.1145/3670414,
  author = {Kayan, Hakan and Heartfield, Ryan and Rana, Omer and Burnap, Pete and Perera, Charith},
  title = {CASPER: Context-Aware IoT Anomaly Detection System for Industrial Robotic Arms},
  year = {2024},
  publisher = {Association for Computing Machinery},
  address = {New York, NY, USA},
  url = {https://doi.org/10.1145/3670414},
  doi = {10.1145/3670414},
  note = {Just Accepted},
  journal = {ACM Trans. Internet Things},
  month = {jun},
  keywords = {neural networks, anomaly detection, industrial robotic arms, cyber-physical systems, ubiquitous computing}
}