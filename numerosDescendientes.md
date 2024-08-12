# Recursividad

## Código ejemplo:
~~~
fun nDescendientes (n:Int)
{
   if(n<=0)
   {
      return
   }
   println(n)
   nDescendientes(n-1)
}
fun main()
{
   val numero=5
   nDescendientes(numero)
}
~~~

## Explicación
Este es un ejemplo donde se ejecuta el codigo teniendo de base el número 5, este numero se va a ir reduciendo a medida que se vaya llamando el código a si mismo hasta llegar a 0.
