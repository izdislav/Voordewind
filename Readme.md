За да се инсталират зависимостите трябва да се инсталира и да се зададе по подразбиране python3.8
```shell
sudo apt install software-properties-common
```

```shell
sudo add-apt-repository ppa:deadsnakes/ppa
```

```shell
sudo apt-cache policy python3.8
```

```shell
sudo apt install python3.8
```

```shell
ls /usr/bin/python*
```

```shell
sudo update-alternatives --install /usr/bin/python python /usr/bin/python3.8 1
```

```shell
sudo update-alternatives --config python
```

и след това да се инсталира python3.8-distutils:
```shell
sudo apt-get install --reinstall python3.8-distutils
```

За инсталиране на docx:
```shell
pip install python-docx
```

