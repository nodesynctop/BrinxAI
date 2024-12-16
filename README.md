# BrinxAI

Twitter / X: https://x.com/BrinxAI_Labs

Official Website :https://brinxai.com

Litepaper
https://brinxai.com/litepaper.pdf

Documentation: https://brinxai.gitbook.io

FAQ (Frequently Asked Questions): https://brinxai.gitbook.io/brinxai-depin-ai/faq

# How to Run BrinxAI Worker Nodes - Linux (Ubuntu)
#### System Requirements for Worker Nodes
<p align="center">
![worker1](https://github.com/user-attachments/assets/d6ab92e3-5444-40cd-884d-5d499c3d34e1)
</p>

## Step 1. Install Docker (If not yet)
```
curl -fsSL https://get.docker.com -o get-docker.sh
sudo sh ./get-docker.sh
```
## Step 2. Pull Worker
```
docker pull admier/brinxai_nodes-worker:latest
```
## Step 3: Run Worker
```
git clone https://github.com/admier1/BrinxAI-Worker-Nodes
cd BrinxAI-Worker-Nodes
chmod +x install_ubuntu.sh
./install_ubuntu.sh
```
`Note: During the installation process, the project requires opening the default port 5011, if you want to use another port, enter it.`

`Open that port on your HomeServer or VPS (if ufw is enabled)`
