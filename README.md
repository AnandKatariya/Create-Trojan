
<h1 align="center">Welcome to Repositorie of how to make Trojan👋</h1>
<p>
<img src="https://img.shields.io/badge/version-0.1-blue.svg?cacheSeconds=2592000" />
</p>
<img src="https://raw.githubusercontent.com/AnandKatariya/Kali-Linux-Jupyter-Notebook-Installation/a9eea7518be7dadfdc60ac934d98e59735590209/Image/made-with-kali-linux.svg" >


### 🏠 [Homepage](https://github.com/AnandKatariya?tab=repositories)
<p align =center >
  <img src="https://eadn-wc05-3736104.nxedge.io/wp-content/uploads/2022/06/Trojan-Horse-Virus_MAIN-IMAGE-scaled.jpeg" height='288' width='512' />
</p>

<h1 align="center">Dont try this at Home, School,Or any other public place!!!</h1>
<br>

<h1 align="center"> Introduction to Trojan</h1>
<p>
 
# Go to Root Terminal
```sh
sudo su
```
## Git clone
```sh
git clone https://github.com/screetsec/TheFatRat.git
```
  ## Go to dictonary
```sh
cd FatRat/
```
## List the  dictonary
```sh
ls
```
So now here you will able to see that setup.sh don't have excuateable permission, So we will give the permission.

## See which file are excuatable
```sh
ls -l
```
So we can see here that this setup.sh file don't have excuatalbe permission only these file have read and write permission, So will give ther permission.

## Give excuatable permission
```sh
chmod +x setup.sh
```
 Now the file name setup.sh will get excuatable permission.
  
  ## Run the file
```sh
setup.sh
```
 It will upgrade all the repository and will autoinstall all the tool which are needed.
  
  ## List the dictonary
```sh
ls 
```
  
## Give excuatable permission to FatRat
```sh
chmod +x fatrat
```
  
## Run the FatRat
```sh
./fatrat
```

  ## Run the setup file
```sh
./setup.sh
``` 
  Now we will able to see that all repository are been updated, But still now we can see that some tools are not been install, As we can see that mingw-32, mingw-w64 are not install so we need to manually install it.

 ## Install mingw-w64
```sh
apt-get install mingw-w64
```
  
   ## Install mingw-32
```sh
apt-get install mingw-32
```
Now all tools have been installed. So now you can run the file and make the Remote Acess Trojan (RAT).

  ## Open the file
```sh
./fatrat
```
 <h3> Now its the end of code you can have fun with this Trojan and just remember don't use it for revenge or any other public place just have fun with this. </h3>

## Author

👤 **Anand Katariya**

* Github: [@AnandKatariya](https://github.com/AnandKatariya)

## 🤝 Contributing

Contributions, issues and feature requests are welcome!<br />Feel free to check [issues page](https://github.com/AnandKatariya/Create-Trojan/issues).

## Show your support

Give a ⭐️ if this project helped you! <br>
Stay tuned for more updates
