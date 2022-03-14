<!---
===========
READ ME
===========

1. Instalar na máquina local uma instância do Portal Lumis XP versão 14.1.0 Developer Stand Alone.
( Arquivo ZIP disponível no FTP ADN: ftp.adn.com.br/Oi-Internet/LUMIS/

2. Ir na pasta de instalação do LUMIS \lumisportal-14.1.0\lumisportal\lumisdata\shared\source

3. Rodar o comando "git clone https://github.com/gr-adn-tecnologia/br.com.blog.git

4. No Portal Lumis (localhost:9080) ir em CONFIGURAÇÔES / DEPLOY e escolher a opção "Indicando a pasta do módulo no diretório de código-fonte.", informando o camninho: "/br.com.blog/src"

5. No Portal Studio, selecionar o projetpo "Blog" e Imnportar o arquivo de conteúdo .LEC 

6. Pronto, o portal Blog (CMS Blog Oi_e) na máquina local está atualziado com o GITHUB.

OBS: para solucionar o erro "filename too long", rodar no console como administrador: git config --system core.longpaths true

--->
