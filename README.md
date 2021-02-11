# ScooterJam
A script to scan for nearby m365 scooters and lock them on their next stop, while leaving your scooter free to leave the others in the dust.
Works great at traffic lights and drag races.


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

Clone the Repository:
```sh
git clone https://github.com/NickJongens/ScooterJam.git
```

## Start the attack - could be run as a cron job etc:
```sh
sudo python ScooterJam.py
```



## Credits

Anton Hakansson
https://github.com/AntonHakansson

Ian Harvey
https://github.com/IanHarvey
