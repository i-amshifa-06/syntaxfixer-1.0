STEPS TO INSTALL

sudo apt install python3-tk -y

echo "deb [trusted=yes] https://i-amshifa-06.github.io/syntaxfixer-repo ./" | sudo tee /etc/apt/sources.list.d/syntaxfixer.list

sudo apt update

sudo apt install syntaxfixer
