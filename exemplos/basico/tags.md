## Usando as tags PHP
  
Existem 3 tipos de tags de abertura e fechamento PHP.  
  
### <?php ?>
  
Essa é a forma padrão de uso e é a recomendada.    
  
```php
<?php
print("Olá Mundo!!!");
?>
```
  
### <? ?>
  
Para usá-la antes da versão 5.4.0 do PHP era necessário habilitá-la no `php.ini` definindo a opção `short_open_tag` como `on`.   
A partir daí não é preciso mudar nada para usá-la.  
  
```php
<?
echo "Olá Mundo!!!";
?>
```

### <script language="php"></script>
  
Parecida com a tag de abertura e fechamento do Javascript em arquivos html.  
Seu uso é desencorajado. Esse recurso pode ser usado até o PHP 5.6.x.  
Não pode ser usado na versão 7 do PHP.  
  
  
### Tag de fechamento `?>`
  
É recomendável não usar a tag de fechamento PHP. Pois pode gerar problemas quando for usado multiplos arquivos para gerar alguma solução.  
  
```php
<?php

print("Olá Mundo!!!");

```  
