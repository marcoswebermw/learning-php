## Configurando o PHP
  

### Instalando o PHP, Apache e Mysql(MariaDB)
    
* No Windows é só baixar e instalar o XAMPP;  
  
* No Linux Debians-Like;
  
```sh
sudo apt install php5 apache2 mysql-server libapache2-mod-php5 php5-mysql
```  
Ou   

```sh
sudo apt install php7.0 apache2 mysql-server libapache2-mod-php7.0 php7.0-mysql
```
  
### Docker
  
* [Usando um servidor lemp](https://github.com/marcoswebermw/meus-dockerfiles/tree/ambiente-lemp).  
     
* Ou baixando a imagem do Php no Docker diretamente:  
    
`docker run -it --rm --name php-1 php:7 bash`  
   
Verifique a versão do PHP na linha de comando:  
   
`php -version`  
  


### Referências
  
* [XAMPP](https://www.apachefriends.org/pt_br/download.html);  
* [Documentação do PHP](http://php.net/manual/pt_BR/index.php);  
