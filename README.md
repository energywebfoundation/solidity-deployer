# solidity-deployer
Automation tool to easily deploy smart contracts.

##Setting up the Environment
1. EWF client installed and running
    - Clone the [repo](https://github.com/energywebfoundation/energyweb-client) and follow the instructions on README.
2. Python 3 installed
3. Solidity [compiler](http://solidity.readthedocs.io/en/develop/installing-solidity.html) installed

##Installing dependencies
- `sudo apt-get upgrade python3 -y`
- `sudo apt-get install python-pip -y`
- `pip install --upgrade pip`
- `pip install virtualenv`
- `virtualenv -p python3 venv`
- `source venv/bin/activate`
- `pip install -r requirements.txt`

##Deploy test the contact
- Insert you own account address and pwd in `deploy.py`.
- Run `python deploy.py`
