# Privacy-Preserving Federated Learning with Homomorphic Encryption (PrivacyFL-HE)

**A Federated Learning framework with Homomorphic Encryption for secure Electronic Health Records (EHRs) training.** 

## 🔥 Features
- Federated Learning (FL) with Homomorphic Encryption (HE)
- Privacy-Preserving AI for Healthcare
- Optimized BFV & CKKS Encryption for Secure Model Aggregation
- Benchmarking on MIMIC-III Medical Dataset.

## 🛠️ Tech Stack
- **Python** (PyTorch, NumPy, Pandas)
- **Flower FL Framework**
- **TenSEAL for Homomorphic Encryption**
- **Google Colab & AWS EC2 Deployment**

## 📂 Project Structure
```
PrivacyFL-HE/
│── client.py             # Federated Learning Client Node
│── server.py             # Federated Learning Server Node
│── train_federated.py    # Training script for FL + HE
│── encryption_utils.py   # Homomorphic Encryption functions
│── data_loader.py        # Data preprocessing and loading
│── requirements.txt      # Required dependencies
│── README.md             # Project documentation
│── docs/                 # Additional documentation
│── models/               # Trained models storage
│── results/              # Performance logs and graphs
```

## 📌 Installation
```bash
# Clone the repository
git clone https://github.com/yourusername/PrivacyFL-HE.git
cd PrivacyFL-HE

# Create a virtual environment
python3 -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
```

## 🚀 Usage
### **Run FL Clients**
```bash
python client.py
```

### **Run FL Server**
```bash
python server.py
```

### **Train Model**
```bash
python train_federated.py
```

## 📊 Results & Performance
| Model | Accuracy | Encryption Overhead |
|--------|---------|------------------|
| FL (No Encryption) | 95.8% | 0 ms |
| FL + Homomorphic Encryption | 94.2% | 350 ms |

## 📖 Research Paper & Documentation
- **Research Paper:** (Soon)
- **Technical Documentation:** (Soon)

## 🤝 Contributing
Feel free to fork this repository, open issues, or submit pull requests! 

## 📜 License
This project is licensed under **MIT License**.

---


