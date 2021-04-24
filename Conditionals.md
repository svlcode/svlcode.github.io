# Conditionals statements

In C# exista mai multe intructiuni de conditionare a executiei codului.

## Instructiunea *if*

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
Console.WriteLine("Sa vedem ce ve face la urmatorul examen.");

```

In exemplul de mai sus, variabila nota are valoare 5 si deci la executia programului se vor afisa ambele mesaje:
*Felicitari ai luat o nota de trecere.*
*Sa vedem ce ve face la urmatorul examen.*
