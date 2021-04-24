# Instructiunea *else*
Instructiunea else este o instructiune decizionala care vine in completarea instructiunii if. Astfel ca ea determina executia codului din interiorul acoladelor asociate instructiunii else atunci cand expresiea din interiorul parantezelor instructiunii if nu este adevarata.

```c#
if (booleanExpression == true) 
{
  // execute code1
  // execute code2
  ...
}
else 
{
  // execute code3
  ...
}
```
Din exemplul de mai sus reiese faptul ca code3 se va executa doar atunci cand booleanExpression este falsa (false).

### Exemplu conditie adevarata


```c#
int nota = 5;

if (nota > 4 == true)
{
  Console.WriteLine("Felicitari, ai luat o nota de trecere!");
}
else
{
  Console.WriteLine("Ne pare rau. Nu ai luat nota de trecere.");
  Console.WriteLine("Sa vedem ce vei face la urmatorul examen.");
}

```

In exemplul de mai sus, variabila nota are valoare 5 si deci la executia programului se vor afisa doar mesajul:
```
Felicitari, ai luat o nota de trecere!
```

### Exemplu conditie falsa

```c#
int nota = 3;

if (nota > 4 == true)
{
  Console.WriteLine("Felicitari, ai luat o nota de trecere!");
}
else
{
  Console.WriteLine("Ne pare rau. Nu ai luat nota de trecere.");
  Console.WriteLine("Sa vedem ce vei face la urmatorul examen.");
}
```

In exemplul de mai sus, variabila nota are valoare 3 si cum 3 nu este mai mare decat 4, la executia programului se vo afisa mesajele:
```
Ne pare rau. Nu ai luat nota de trecere.
Sa vedem ce vei face la urmatorul examen.
```


## Acolade optionale
La fel ca la instructiunea if, in cazul in care bucata de cod contionata este doar o singura linie de cod, acoladele sunt optionale. Este de preferat totusi, dar nu obligatorie, mentinerea indentarii liniei de cod conditionata. 
```c#
int nota = 3;

if (nota > 4 == true)
  Console.WriteLine("Felicitari, ai luat o nota de trecere!");
else
  Console.WriteLine("Ne pare rau. Nu ai luat nota de trecere.");
Console.WriteLine("Sa vedem ce vei face la urmatorul examen.");
```
In exemplul de mai sus mesajul, '*Sa vedem ce vei face la urmatorul examen.*', se va afisa indiferent de valoarea notei.