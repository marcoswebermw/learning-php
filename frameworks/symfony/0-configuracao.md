## Configurando o Symfony
  
É necessário ter instalado:  
  
* O `php7` ou versões superiores;  
* O `composer`.  
  
### Criando um novo projeto
  
`composer create-project symfony/skeleton meu-projeto`  
  
Será gerado um novo diretório com arquivos e subdiretórios do symfony para o projeto, além de baixadas algumas dependências.  
  
### Executando a aplicação
  
O projeto symfony recomenda usar em produção um webserver como `Apache` ou `Nginx`. Mas para desenvolvimento eles oferecem o `Symfony PHP Web Server`.  
  
É necessário entrar dentro do diretório raíz do novo projeto criado e instalar o servidor do symfony.  
  
```sh
cd meu-projeto
composer require server

php bin/console server:run
```
  
Uma página de boas-vindas pode ser visualizada em `http://localhost:8000/`.  
  
> Se estiver rodando de uma maquina virtual diga para o servidor liberar todos os ips para poder ser acessada de fora através de:  

```sh
php bin/console server:start 0.0.0.0:8000
```  
  
### Outras informações

Será criado e gerenciado um `.gitignore`  automaticamente se estiver usando o Git através de uma ferramenta chamada `Flex`.    
  
### Referências
  
[Documentação do Symfony](https://symfony.com/doc/current/setup.html);  
