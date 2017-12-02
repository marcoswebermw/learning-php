## Outras configurações do Symfony
  
É possível que o Symfony não rode como esperado por falta de algum requisito.  
É disponibilizada uma ferramenta para fazer a verificação desses requisitos chamada `requirements-checker`. Para usá-lo entre na raiz do projeto e faça o seguinte:   
   
`composer require req-checker`  
  
Serão adicionados dois scripts em sua aplicação.  
  
* `vendor/bin/requirements-checker` - Faz a verificação dos requisitos da linha de comando;  
* `public/check.php` - Faz a verificação dos requisitos do servidor web;  
  
```sh
php vendor/bin/requirements-checker  
```  
  
No navegador entre em `http://localhost:8000/check.php`:  
  
Assim que fizer as verificações e constatar que tudo funciona corretamente remova os scripts para evitar problemas de segurança futuras:  

`composer remove req-checker`    
  
### Continuando um projeto Symfony
  
Caso esteja continuando um projeto Sympony em um lugar diferente do habitual, use o comando abaixo dentro do diretório raiz para baixar as dependências no diretório `vendor`:  
  
`composer install`  
  
### Segurança na instalação e atualização de dependências
  
O Symfony oferece um verificador de vunerabilidades em dependências. Se instalado, esse verificador executa uma checagem toda vez que uma dependência for instalada ou atualizada, mostrando uma mensagem caso surja alguma vunerabilidade conhecida na dependência.  
  
Para instalá-lo entre no diretório raiz do projeto e digite:  
   
`composer require sec-checker`    
  
  
### Referências
  
* [Symfony Setup](https://symfony.com/doc/current/setup.html);  
  
  

 