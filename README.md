GNRE PHP (branch em desenvolvimento)
=================

##Atenção
Essa não é a branch principal do projeto, essa é a branch em desenvolvimento onde está sendo implementada a nova feature para exibir a guia em PDF.
Para visualizar a branch master [clique aqui](https://github.com/marabesi/gnrephp/tree/master)

Objetivo
-----
 API possibilita a comunicação com a SEFAZ para a emissão da nota GNRE (Guia Nacional de Recolhimento de Tributos Estaduais). 
 A API GNRE tem como maior inspiração a API NFEPHP que você pode encontrar através do link https://github.com/nfephp

Dependências
-------
* [Apache](http://httpd.apache.org/) / [Nginx](http://nginx.org/)
* [PHP 5.3+](http://php.net)
* Extensões PHP
 * [DOMDocument](http://br2.php.net/manual/en/domdocument.construct.php)
 * [cURL](http://br2.php.net/manual/book.curl.php)

------

Documentação
------
* Documentação da GNRE PHP gerada com o PHPDOC pode ser visualizada [aqui](http://marabesi.github.io/gnrephp/doc/namespaces/Gnre.html)

* Nosso wiki de como utilizar a API e gerar as GNRES está disponível [aqui no github](https://github.com/marabesi/gnrephp/wiki)

Instalação via composer
------
Adicionando a GNRE PHP em um projeto existente com o composer

Caso você não possua o composer veja [esse link](https://getcomposer.org/doc/01-basic-usage.md) antes de prosseguir

Adicione a dependência da GNRE PHP no arquivo composer.json :

"marabesi/gnre": "dev-master"

Atualize suas depedências existentes no composer :

composer update

-----
Quick start
-----
git clone https://github.com/marabesi/gnrephp.git

-----

Mais informações
-----
Site oficial do governo :     http://www.gnre.pe.gov.br/gnre/index.html

Site do Projeto : http://marabesi.github.io/gnrephp/



