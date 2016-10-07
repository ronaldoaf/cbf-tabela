# cbf-tabela
Classe que retorna os dados jogos do Campeonato Brasileiro e várias outras competições utilizando como fonte de dados o site da CBF


##Para instalar 

```

composer require ronaldoaf/cbf-tabela
 
```


##Exemplo de uso

```php
<?php 
require __DIR__.'/vendor/autoload.php';


$tabela = new \Ronaldoaf\Tabela;

echo $tabela->rodada_atual;

print_r($tabela->rodadas);

 
```


