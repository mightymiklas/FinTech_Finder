# FinTech_Finder
UW FINTECH 2021-22 MODULE XIX Challenge

-Hire a FinTech Professional and make payments via cryptocurrency. 

## Requirements
This program uses the following libraries:
- Streamlit
- Dotenv
- bip44
- web3

To run this program, perform the following steps:
1. Clone the github repository
```shell
git clone https://github.com/mightymiklas/FinTech_Finder.git
```
2. Change to the new directory:
```shell
cd FinTech_Finder
```
3. Install the required packages in a conda environment (replace "myenv" with an environment name of your choice):
```shell
conda create -n myenv python=3.7
```
4. Install the required packages:
```shell
pip install -r requirements.txt
```
5. Run the program:
```shell
streamlit run fintech_finder.py
```

## Usage
To run this program insert your mnemonic from Ganache suite in the sample.env file and then rename file to (dot)env and save. 

```
MNEMONIC='xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx xxxx'
```

## Example
![Example](Images/screenshot.png)

