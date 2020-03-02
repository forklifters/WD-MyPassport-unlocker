# WD-MyPassport-unlocker
unlock WD My Passport on linux 



-Install required packages:

```bash
sudo apt-get install python-pip python-dev lsscsi
```
 
-Install py_sg library:

```bash
sudo pip install py_sg
```

-Download wd utils to your home directory:

```bash
cd ~; wget https://raw.githubusercontent.com/evox95/wdpassport-utils/master/wdpassport-utils.py
```

-add excusion permissison

```bash
chmod +x ~/wdpassport-utils.py
```

*Everything is ready*

-to unlock run 

```bash
~/wdpassport-utils.py -u
```


#### reference
[How to unlock `WD My Passport Drive` on Linux](https://blog.bestcoding.net/en/unlock-wd-passport-drive-linux/)
