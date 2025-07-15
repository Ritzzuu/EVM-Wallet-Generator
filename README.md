# EVM Wallet Generate bot
The EVM Wallet Generator project is a Python-based utility designed to generate public-private key pairs compatible with the Ethereum Virtual Machine (EVM) network. Its goal is to provide a fast and automated way to create new wallet addresses and their corresponding private keys. This application solves the problem of creating large numbers of wallets, which may be required for various purposes such as testing dApps, blockchain research, or other development needs. The wallet creation process is performed locally and deterministically, ensuring the security of the private key during the generation process. The primary users of this project are developers, researchers, or anyone who needs the ability to efficiently generate multiple EVM wallets without manual interaction with conventional wallet interfaces.

# Features
* **Fast Wallet Generator:** Generate public-private key pairs quickly and efficiently.
* **EVM Compatibility:** The resulting wallet is compatible with all Ethereum Virtual Machine networks.
* **Deterministic Generation:** Ensures deterministic wallet generation for consistent reproduction.
* **Local Operation:** Completely local operation, no keys are sent to external servers.
# Getting Started
The following instructions will help you get this project up and running in your local environment.
# Requirements
Make sure you have the following software installed on your system: 
* Python 3.6 or later
* pip (Python package installer), usually included with the Python installation
# Installation
Follow these steps to install the project
1. Clone this repository to your local machine using git clone
```bash
https://github.com/Ritzzuu/EVM-Wallet-Generator.git
```
2. Go to the project directory
```bash
cd EVM-Wallet-Generator
```
3. Install the required dependencies using pip install with the requirements.txt file.
```bash
pip install -r requirements.txt
```
# Run
Once the installation is complete, you can run the script to start generating your wallet. Run the main index.py script from the project root directory.
```bash
python index.py
```
The output will display a list of generated wallet addresses and private keys.
