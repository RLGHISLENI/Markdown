### Tags

+ Arquivos PHP **DEVEM** usar somente as tags <?php e <?=
+ Proibido usar:
  - short open tags (<?) 
  - tags ASP (<%)
  - tags de script (<script language="PHP">)

### Codificação de arquivos PHP

+ **DEVEM** usar somente a codificação UTF-8 sem BOM (Byte Order Mark)

### Nomes de classes e namespaces

+ **DEVEM** ser decarados em StudlyCaps
  - PrimeiraClasse

```php
<?php
// PHP 5.3 and later:
namespace Vendor\Model;

class Foo
{
  // class body
}
```

### Constantes

+ **DEVEM** ser declaradas com letras maiúsculas e separadas por underscores \_
 - UMA_CONSTANTE

```php
<?php
namespace Vendor\Model;

class Foo
{
  const VERSION = '1.0';
  const DATE_APPROVED = '2019-05-27';
}
```

### Nomes de métodos 

+ **DEVEM** ser declarados em camelCase
  - meuMetodo()



### Argumentos
+ Espaço após cada argumento  
+ Similar a escrita

```php
public function foo($arg1, &arg2, $arg3 = [])
{
  // methodbody
}
```

+ PODE-SE usar múltiplas linhas

```php
public function aVeryLongMethodName(
    Type $arg1,
    &arg2, 
    $arg3 = []
) {
  // methodbody
}
```

### Exceções

```php
<?php
try {
  // try body
} catch (FirstExceptionType $e) {
  // catch body
} catch (FirstExceptionType $e) {
  // catch body
}
```
