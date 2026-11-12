# Simple-Circuit-Simulator

# Starting app

# clone github like this or download it manually (skip git clone)
git clone https://github.com/OliviaKozubal/Simple-Circuit-Simulation.git

# go to app directory
cd Simple-Circuit-Simulation

# create virtual environment
python3 -m venv .venv

# activate environment (Windows)
.venv\Scripts\activate

# if you can't create virtual enviroment because running scripts is disabled on your system run this line to:

# temporarily change it
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process

# permamently change it for your user only
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser



# install required python packages
pip install -r .\Simple-Circuit-Simulation\requirements.txt

# to leave virtual enviroment
deactivate
