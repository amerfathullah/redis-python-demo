# redis-python-demo

## Overview

This is a repository for Redis-Python demonstration.

## Dependencies

- python 3.x
- redis
- jupyter notebook

## Installation

1. Download and install Redis. There are 2 ways to install Redis for Windows. Choose only ONE of them.

- Microsoft Archive (old version, easy install)

I'm using this version for the demo. Download and install Redis installation file from [here](https://github.com/microsoftarchive/redis/releases/tag/win-3.0.504). To verify that Redis successfully installed in your machine. run ```redis-cli``` inside your terminal.

- WSL Ubuntu

Enable WSL in your Windows machine by following this [guide](https://docs.microsoft.com/en-us/windows/wsl/install-win10). After successfully following the guide, open your Ubuntu terminal, create Linux username and password, and run this:

```
sudo apt-get update
sudo apt-get upgrade
sudo apt-get install redis
```

Run ```redis-server``` to initiate Redis. Open another Ubuntu terminal and run ```redis-cli``` and you're done!

2. Install the Python library required for this project:
```
pip install redis
```

1. Now you can open and run the notebook file using Jupyter Notebook.
