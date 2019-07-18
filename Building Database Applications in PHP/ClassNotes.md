#### 0718


Some notations beforehand
---
Use `::` to access **static** item, a string constant or a static method, in a **class**. You can just call this static method of a class without instantiating an object. e.g.:

`echo DateTime::RFC822."\n";`

Use `->` to access item in an **object**,this is **daynamic**. Most things are dynamic. e.g.:

`echo $z->format('Y-m-d')."\n";`
<!---
<p align="center">
  <b>----I am the real starting line----</b>
</p>
--->
Object Life Cycle in PHP
---
Object Oriented approach was not introduced to PHP until PHP 5. 

Objects are created, used and discarded.((｡•́︿•̀｡)poor objects...)
Constructors are used a lot but destructors are seldom used. Garbage collector will take care of calling the destructors. e.g.:

```
class PartyAnimal {
    function __contruct() {
      echo("Constructed\n"):
    }
    function __somthing() {
      echo("Something\n"):
    }
    function __destruct() {
      echo("Destructed\n"):
    }
}

echo("--One\n");
$x = new PartyAnimal();
echo("--Two\n");
$y = new PartyAnimal();
echo("--Three\n");
$x->something();
echo("--The End?\n");
  
```
this prints out:

```
--One
Constructed
--Two
Constructed
--Three
Something
--The End?
Destructed
Destructed
```

use keyword `new` to instantiate an object from class in PHP, e.g.:
`$z = new DateTime('2012-01-31');`

The parameters for constructing new object is passed by the method starting with `__`, e.g.:

`public __construct([string $time = "now" [, DateTimeZone $timezone = NULL]])`





