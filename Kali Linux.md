1. To make update :

```
sudo apt update
```

2. To make upgrade :

```
sudo apt upgrade
```

3. To get full upgrade :

```
sudo apt full-upgrade
```

-------------------------------------------------------------------

4. **For enable Bluetooth :**

  1. Step 1 

```
sudo apt install bluez*
```

  2. Step 2

```
sudo apt install blueman
```

   3. Step 3

```
sudo systemctl enable bluetooth.service
```

-------------------------------------------------------------------

5. To install program .deb

```
sudo dpkg -i <file PATH>
```
