Title: Instalando apps pelo terminal com homebrew casks
Date: 2014-01-25 17:00
Category: Mac
Tags: mac, homebrew, cask
Slug: instalando-aplicativos-com-homebrew-casks
Author: Filipe Ximenes
Summary: Conheça um pouco sobre o homebrew cask, uma ferramenta que permite instalar aplicações GUI no Mac pelo terminal.

Instalar aplicativos no Mac não é uma atividade muito prazerosa, especialmente se você já teve contato com as ferrametas de gerenciamento de pacotes de linux. Ficar arrastando aplicativos para a pasta, ou clicando pelos menus de instalação se torna ainda mais tediante se você tiver que fazer isso várias vezes seguidas quando está trocando de computador.   
Há algum tempo o [homebrew](http://brew.sh/) já é a ferramenta padrão dos desenvolvedores para gerenciamento de pacotes no Mac, mas agora é possível torna-lo ainda mais poderoso com o [homebrew cask](https://github.com/phinze/homebrew-cask). Esta ferramenta permite instalar aplicativos com apenas um comando e nada mais, basta digitar ```brew cask install dash```  e você terá o [Dash](http://kapeli.com/dash) no seu diretório de aplicativos.   
Para instalar o cask, execute ```brew install phinze/cask/brew-cask```. Os camandos básicos são:   

```brew cask search [nome-da-aplicação]```   
```brew cask install [nome-da-aplicação]```   
```brew cask uninstall [nome-da-aplicação]```   

Além das vantágens já citadas, o cask também guarda o que for instalado num diretório separado e gera links para eles na pasta de Aplicativos, evitando conflitos e deixando seu computador mais organizado.   
Para quem usa o [Alfred App](http://www.alfredapp.com/) (que também pode ser instalado via cask), é preciso executar o comando ```brew cask alfred``` para que ele possa reconhecer os aplicativos instalados pelo cask.
