# Conditionals statements

In C# exista mai multe intructiuni de conditionare a executiei codului.

## Instructiunea *if*
Instructiunea if este o instructiune decizionala. Determina executia codului din interiorul acoladelor in functie de valoarea de adevar a expresies din interiorul parantezelor. Codul se va executa astfel:
- Daca expresia booleana din paranteze este adevarata (**true**), atunci se va executa codul dintre acolade (*code1*).
- Daca expresia este falsa (**false**) atunci firul de executie nu va executa codul din interiorul acoladelor, ci va sari imediat la executia codului din afara acoladelor *code2*.

```c#
if (booleanExpression == true) 
{
  // execute code1
}
// execute code2
```

### Exemplu conditie adevarata


```c#
int nota = 5;

if (nota > 4 == true)
{
  Console.WriteLine("Felicitari ai luat o nota de trecere.");
}
Console.WriteLine("Sa vedem ce vei face la urmatorul examen.");

```

In exemplul de mai sus, variabila nota are valoare 5 si deci la executia programului se vor afisa ambele mesaje:

*Felicitari ai luat o nota de trecere.*

*Sa vedem ce vei face la urmatorul examen.*


### Exemplu conditie falsa


```c#
int nota = 4;

if (nota > 4 == true)
{
  Console.WriteLine("Felicitari ai luat o nota de trecere.");
}
Console.WriteLine("Sa vedem ce ve face la urmatorul examen.");

```

In exemplul de mai sus, variabila nota are valoare 4 si cum 4 nu este mai mare decat 4, la executia programului se va afisa doar mesajul:

*Sa vedem ce vei face la urmatorul examen.*

## Acolade optionale
In cazul in care bucata de cod contionata este doar o singura linie de cod, acoladele sunt optionale. Este de preferat totusi, dar nu obligatorie, mentinerea indentarii liniei de cod conditionata. Exemplul de mai sus poate fi scris si astfel:

```c#
int nota = 4;

if (nota > 4 == true)
  Console.WriteLine("Felicitari ai luat o nota de trecere.");
Console.WriteLine("Sa vedem ce vei face la urmatorul examen.");

```
