# Ruby Cucumber Capybara

CONFIGURANDO AMBIENTE: 

MACOS:
Instalar o homebrew > RUBY -E "$(curl -fssl https://raw.githubusercontent.com/homebrew/install/ master/install)"
Instalar o Rbenv > brew install rbenv ruby-build
Executar o comando > echo 'if which rbenv > /dev/null; then eval "$(rbenv init -)";
fi' >> ~/.bash_profile
Executar o comando > source ~/.bash_profile
Instalar versão específica do Ruby > rbenv install 2.4.2 > rbenv global 2.4.2 > ruby -v
Instalar o bundler > gem install bundler
Baixar driver chrome e colocar na pasta usr/local/bin (https://sites.google.com/a/chromium.org/chromedriver/)
Baixar driver firefox e colocar na pasta (https://github.com/mozilla/geckodriver/releases)

WINDOWS: 
Instalar Ruby > http://rubyinstaller.org/downloads/
Instalar o bundler > gem install bundler
Baixar driver chrome (https://sites.google.com/a/chromium.org/chromedriver/) e colocar na pasta C:/ 
Baixar driver firefox (https://github.com/mozilla/geckodriver/releases) e colocar na pasta C:/

INSTALANDO GEMS: 
Abra o terminal na pasta testes/ e execute > bundle install

RODANDO PROJETO: 
comando <cucumber> no terminal. 
RODANDO POR TAG
comando <cucumber -t '@tag'>


