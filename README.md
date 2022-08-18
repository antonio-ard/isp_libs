# install introduction
```shell
curl -s --compressed "https://${GITHUB_USERNAME}.github.io/my_ppa/KEY.gpg" | sudo apt-key add -  

sudo curl -s --compressed -o /etc/apt/sources.list.d/my_list_file.list "https://antonio-ard.github.io/isp_libs/my_list_file.list"  

sudo apt update 
```
    sudo apt install arducamconfigparser;  
    sudo apt install arducamisp;
    sudo apt install arducamlib;
