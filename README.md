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
<img src="https://github.com/user-attachments/assets/d6ab92e3-5444-40cd-884d-5d499c3d34e1" />
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

Check open ports: https://portchecker.co

## Step 4: Go to this page to register an account or login (if you already have one): 

Register account: https://workers.brinxai.com/register.php?ref=4bf51063

Select Add Worker Node -> Enter NodeName -> Enter node IP -> Enter the port provided above -> Add Node-
<p align="center">
<img src="https://github.com/user-attachments/assets/8afb4cbb-f4d7-40ff-8275-66ee008888fd"
</p>
Then wait about 5-10 minutes for the node to be activated
  
## Step 5: Models configuration

Click "Models" -> View the configuration of the models that your device can meet)
<p align="center">
<img src="https://github.com/user-attachments/assets/752abe5e-e13f-410a-bf74-fc22a73ccd30"
</p>

Click "Manually Turn On Models" -> copy the models that can run with your configuration
<p align="center">
<img src="https://github.com/user-attachments/assets/dddfa20b-dd55-49a3-8c79-0bb2a65958b6"
</p>

