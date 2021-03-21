# Norminette_42
Installer la norminette **pour les nuls.**

## 1. Pré-requis

Installer homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
[HomeBrew](https://brew.sh/index_fr)

Installer ruby
```
gem install bunny
brew install ruby
sudo xcode-select --install
```
Si cette derniere commande ne fonctionne pas faire : 
Cela installera probablement un logiciel.
```
sudo rm -rf /Library/Developer/CommandLineTools
```
Ensuite installer json
```
sudo gem install json
```

## 2. Installer la Norminette

[Norminette 42Paris](https://github.com/42Paris/norminette)

Cloner le repo dela norminette 42
```
git clone https://github.com/42Paris/norminette.git ~/.norminette/
cd ~/.norminette/
bundle
```
Créer un alias
```
echo 'alias norminette="~/.norminette/norminette.rb"' >> ~/.zshrc
source ~/.zshrc
```

# La nouvelle Norminette de 42 en python

## 1. Pré-requis

Installer homebrew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
[HomeBrew](https://brew.sh/index_fr)

Installer python3
```
brew install python3
```
Installer ```pip``` avec ```easy_install```
```
curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py
sudo easy_install pip
```
[Easy Install](https://ahmadawais.com/install-pip-macos-os-x-python/)

## 2. Installler la Norminette

[Norminette 42School](https://github.com/42School/norminette)

Cloner le reposiory
```
gcl https://github.com/42School/norminette.git
cd norminette
```
Installer en utilisant pip
```
python3 -m pip install --upgrade pip setuptools
python3 -m pip install norminette
```
