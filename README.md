# ScooterJam
A script to scan for nearby m365 scooters and lock them if they don't have a bluetooth connection active.


## Installation of pip and modules

```sh
sudo apt-get install python-pip libglib2.0-dev
```

```sh
sudo pip install bluepy
```

```sh
sudo pip install git+https://github.com/AntonHakansson/m365py.git#egg=m365py
```

## Find MAC address for scooter

This package includes the option to scan and list nearby M365 Scooters.
Simply excecute the package as such:

```sh
sudo python -m m365py
```
