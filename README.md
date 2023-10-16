# Install python3.11 on Ubuntu20:

```
sudo apt install software-properties-common
sudo add-apt-repository ppa:deadsnakes/ppa -y
sudo apt install python3.11 python3.11-venv
```

Ensure that your python11 is applied:

```
sudo update-alternatives --install /usr/bin/python python /usr/bin/python3.11 2 
sudo update-alternatives --install /usr/bin/python3 python3 /usr/bin/python3.11 2
```

# Create hass venv

```
script/setup
```


# Apply hass venv

```
source venv/bin/activate
```


# IDE

Start your IDE of choice in the venv. There you can then also debug the hass application, which is located here:

```
venv/bin/hass
```

