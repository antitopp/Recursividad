## Recursividad
#### La Recursividad es una tecnica que permite a las funciones autoinvocarse para resolver probles complejos.
~~~ 
fun nDescendentes (n:Int)
{
   if(n<=0)
   {
     return
   }
   println(n)
   nDescendentes(n-1)
}
fun main()
{
   val numero=5
   nDescendentes(numero)
}
~~~
### Caso Base
Es una condicion, su funcion es terminar la Recursion y de esta forma evitar que se forme el ciclo infinito.
### Llamada Recursiva
La funcion se llama a si misma.
