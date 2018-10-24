# CodingStyle
Coding style I use for PHP and C#. My current coding style is dictated by what I use at work to keep consistency. 


## PHP 

### Casing
Camel casing starting with lower case for funtion/var names and all upper for class names.
```php 
$myVariableName = 'Awesome';

class MyClassName {}

function myFunctionName(){}
```
 

### Class/Interface/Abstract definitions
```php 
class MyAwesomeClass implements MyAwesomeInterface {

  $dependencyInjection; 
  
  public function __construct($diInjection) {
    $this->dependencyInjection = $diInjection;
  }
  
}
```
