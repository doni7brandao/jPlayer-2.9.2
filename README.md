# [jPlayer](http://jplayer.org/) : HTML5 Audio & Video para [jQuery](http://jquery.com/)

Suporte para [Zepto](http://zeptojs.com/) 1.0+ compilado com módulo de dados.

## O que é o jPlayer?

### jPlayer é um plugin jQuery/Zepto que permite:
* **reproduzir e controlar** arquivos de **mídia** em sua página da web.
* criar uma **interface e experiência consistente** em todos os navegadores.
* criar e estilizar uma media player usando **apenas HTML e CSS**.
* adicionar **áudio** e **vídeo** aos seus projetos jQuery/Zepto.
* suporta mais dispositivos utilizando o **HTML5**.
* suprte a navegadores mais antigos usando um recuro de _retorno/encaminhamento_ do Flash.
* controlar a mídia em seu site usando uma [API JavaScript](http://www.jplayer.org/latest/developer-guide/).

### jPlayer suporta:
* HTML5: **mp3, m4a (AAC), m4v (H.264),** ogv*, oga*, wav*, webm*
* Flash: **mp3, m4a (AAC), m4v (H.264),** rtmp, flv.

_(*)  Formatos opcionais de contrapartida para aumentar o suporte ao navegador HTML5._

## Instalação do Bower
* instalação simples usando `bower install jplayer`
* veja <http://bower.io/> para mais informações.

## Instalação do Composer

Instale o jPlayer via composer adicionando as seguintes linhas ao seu `composer.json` no seu projeto:

    // ...
    "require": {
        // ...
        "happyworm/jPlayer": "2.*"
        // ...
    }
    // ...
    "config": {
        "component-dir": "your/desired/asset/path"
    },
    // ...

Em seguida, execute o seguinte:

    php composer.phar update

O Composer agora fará download de todos os componentes e instalará os arquivos necessários `your/desired/asset/path`, prontos para uso.

## Licença
[jPlayer](http://jplayer.org/) é licenciado sob a licença do [MIT license](http://opensource.org/licenses/MIT).

## Mais informações:
* [jPlayer.org](http://jplayer.org/)
* [Quick Start Guide](http://www.jplayer.org/latest/quick-start-guide/)
* [Developer Guide and API Reference](http://www.jplayer.org/latest/developer-guide/)

## Autor:
Mark J Panaghiston [@thepag](http://twitter.com/thepag)
[happyworm.com](http://happyworm.com/)

## Scripts alimentados a partir deste respositório para: [baixagrandenews.com](https://www.baixagrandenews.com/)
* [Estilo CSS jPlayer](https://doni7brandao.github.io/jPlayer-2.9.2/dist/skin/pink.flag/css/jplayer.pink.flag.min.css)
* [jquery.min.js](https://doni7brandao.github.io/jPlayer-2.9.2/lib/jquery.min.js)
* [jquery.jplayer.min.js](https://doni7brandao.github.io/jPlayer-2.9.2/dist/jplayer/jquery.jplayer.min.js)
