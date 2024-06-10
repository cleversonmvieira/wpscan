# wpscan
Intslando WPSCAN no linux

1) Instalando dependências

sudo apt install ruby ruby-dev build-essential patch zlib1g-dev liblzma-dev

ou

sudo apt install ruby ruby-dev

sudo apt install build-essential patch

sudo apt install zlib1g-dev liblzma-dev


2) Instalando o WPSCAN (Utilizando o RubyGems: sistema de pacotes Ruby)

sudo gem install wpscan

3) Testando o WPSCAN

wpscan --url domínio
Exemplo: wpscan --url github.com
