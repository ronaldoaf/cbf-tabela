# cbf-tabela
Classe que retorna os dados jogos do Campeonato Brasileiro e várias outras competições utilizando como fonte de dados o site da CBF


##Para instalar 

```

composer require ronaldoaf/cbf-tabela
 
```


##Exemplo de uso
Retorna o número da rodada atual e tabela do Brasileirão temporada atual
```php
<?php 
require __DIR__.'/vendor/autoload.php';


$tabela = new \Ronaldoaf\Tabela;

echo $tabela->rodada_atual;

print_r($tabela->rodadas);

```


Retorna a tabela da Série B de 2015
Equivalente a url http://www.cbf.com.br/competicoes/brasileiro-serie-b/tabela/2015
```php
<?php 
require __DIR__.'/vendor/autoload.php';


$tabela = new \Ronaldoaf\Tabela('brasileiro-serie-b','2015');

print_r($tabela->rodadas);

```






