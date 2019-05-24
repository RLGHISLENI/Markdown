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
