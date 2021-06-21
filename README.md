# PIP-Version-Update-Downgrade
PIP How to check Version, Install a specific version , Update or downgrade an version
#Python Files:
Command Prompt and type - where python

Checking PIP Version :
pip --version

Upgrade PIP:
python -m pip install --upgrade pip
(We can verify the version with pip --version)

Downgrade PIP:(for example to 20.0)
python -m pip install pip==20.0
(After that we can verify by pip --version)

Installing Specific Version of PIP:(for example 19.2.2)
python -m pip install pip--19.2.2
(# It'll uninstall, and install 19.2.2 ; Now we can check version by typing pip --version)
