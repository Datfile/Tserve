# 🔧 TorchServe API Wrapper with Auto-Benchmarking

A secure and production-ready Python package to serve PyTorch models using TorchServe, with built-in API wrapper, performance benchmarking tools, and example notebooks.

---

## 🚀 Features

- 🔐 **Secure REST API** with token-based authentication
- 🧠 **Model Deployment** using [TorchServe](https://pytorch.org/serve/)
- ⚙️ **Auto-Benchmarking**: latency, throughput, and performance visualization
- 📦 **Python Wrapper** for easy interaction:  
  ```python
  from TServe import ModelAPI
  api = ModelAPI(api_key="your_key")
  response = api.predict(tensor_input)
