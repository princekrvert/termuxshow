
#! data/data/com.termux/usr/bin/bash
apt update && apt upgade
apt install git 
apt-get install cmatrix
apt install python -y
apt install toilet
apt update && apt upgade
read -p "enter your name " name
toilet " $name " --metal
 pkg install cmatrix
 
 
 echo -e  " \e[35m //////// tools /////////// \e[0m"
 echo -e "\e[35m ****************************** \e[0m"
 echo -e "\e[38m ****************************** \e[0m"
 
echo -e "\e[33m ****************************** \e[0m"
 
 echo -e "\e[32m ****************************** \e[0m"
 echo -e "\e[33m ****************************** \e[0m"
 echo -e " \e[32m 1. banner \e[0m"
 echo -e " \e[32m 2. fbi \e[0m"
 echo -e " \e[32m 3. hacking effect \e[0m"
 echo -e " \e[32m 4. cowsay \e[0m"
 echo -e " \e[32m 5.about \e[0m"
 
  echo -e "\e[36m=====================================================\e[0m"
 read -p " type your choise " too 
 
 case  $too  in
 
 "1")
 echo -e "\e[32m banner installing \e[0m" 
 git clone https://github.com/Bhai4You/Termux-Banner
 cowsay pkg installed " $name "
 
  ;;
 
 "2")
 echo -e "\e[32m fbi installing \e[0m" 
git clone https://github.com/xHak9x/fbi.git
cowsay pkg installed " $name "
