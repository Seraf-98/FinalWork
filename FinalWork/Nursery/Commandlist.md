## Task 1
mkdir Nursery    
cd Nursery    
cat > home_animals    
cat > pack_animals    
cat home_animals pack_animals > animals    
cat animals    
mv animals Human_Friends    
ls -ali    

## Task 2
cd    
mkdir Nursery_system    
cd Nursery    
mv Human_Friends ~/Nursery_system    
cd ~/Nursery_system    
ls -ali    

## Task 3
sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb    
sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb    
sudo apt-get update    
sudo apt-get install mysql-server    

## Task 4
sudo wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb    
sudo dpkg -i google-chrome-stable_current_amd64.deb    
sudo dpkg -r google-chrome-stable