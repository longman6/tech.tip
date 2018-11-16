# brew 설치
 * ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)" 

# mysql install ( version 5.7 )
 * brew install mysql@5.7  
 * echo 'export PATH="/usr/local/opt/openssl/bin:$PATH"' >> ~/.zshrc
 * source ~/.zshrc
 * brew services start mysql@5.7
 * mysql_secure_installation
 * CREATE DATABASE myapp
 * CREATE USER 'homestead' IDENTIFIED BY 'secret'
 * GRANT ALL PRIVILEGES ON myapp.* TO 'homestead';
 * FLUSH PRIVILEGES;