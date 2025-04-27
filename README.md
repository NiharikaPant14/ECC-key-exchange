# **🔐 ECC-based Key Exchange Simulation and Comparative Study 🔑**

## **📄 Project Description**

This project implements an **Elliptic Curve Cryptography (ECC)** based **key exchange protocol** (Elliptic Curve Diffie-Hellman, ECDH) from scratch, with an emphasis on **performance** and **security** considerations. The goal of this project is to simulate the key exchange process between two parties (Alice and Bob), comparing the performance and security across multiple ECC curves (Curve25519 and secp256r1). Additionally, the project demonstrates the use of the shared secret for **symmetric encryption** and simulates a **Man-in-the-Middle (MITM) attack** to showcase the importance of **authenticated key exchange**.

🚧 **Project in Progress**: This is an ongoing project for our **Bachelor's Thesis Project (BTP)** at college, being developed by **[Niharika Pant](https://github.com/NiharikaPant14/NiharikaPant14)** and **[Sneha Pal](https://github.com/Snehapal0709)**.

## **🔑 Key Features**
- **ECC Key Exchange Implementation**: Implemented from scratch using modular arithmetic and elliptic curve operations.
- **Curve Comparison**: Support for different elliptic curve configurations (Curve25519, secp256r1).
- **Security Enhancements**: Added **scalar blinding** to mitigate timing attacks.
- **Performance Benchmarking**: Measured and compared the performance of ECC key exchange and encryption across curves.
- **MITM Attack Simulation**: Demonstrated how without authentication, an attacker can intercept and manipulate key exchange.
- **Symmetric Encryption**: Secured communication using the shared secret derived from the ECC key exchange.

## **🛠️ Technologies Used**
- **Programming Language**: Python 🐍
- **Libraries**: NumPy, Cryptography, Matplotlib 📊
- **Environment**: Google Colab ☁️

## **⚙️ Setup and Installation**
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ECC-Key-Exchange.git
   ```

2. Install necessary libraries:
    ```bash
    pip install numpy cryptography matplotlib
    ```

## **🚀 How to Run the Code**

1. Open the notebook file (`ecc_key_exchange.ipynb`) in **Google Colab**.
2. Run the notebook cells sequentially to:
   - Set up the **ECC operations** and **key generation**.
   - Perform the **key exchange** and derive **shared secrets**.
   - Benchmark performance for different **ECC curves**.
   - Run **encryption** and **decryption** using the shared secret.
   - Simulate the **MITM attack** and visualize results.

## **📂 Project Structure**

- `ecc_key_exchange.ipynb`: The main Jupyter notebook with code for ECC operations, key exchange, and simulations.
- `performance_benchmarks/`: Folder containing benchmark results and plots.
- `README.md`: Project description and instructions.
