Lo que acabamos de ver es cómo modelar fácilmente conjuntos de cosas. Mediante el uso de `[]`, en JavaScript contamos con una manera simple de agrupar esos elementos en listas.

¿Acaso hay una cantidad máxima de elementos? ¡No, no hay límite! Las listas pueden tener cualquier cantidad de elementos.

Y no sólo eso, sino que además, el orden es importante. Por ejemplo, no es lo mismo `["hola", "mundo"]` que `["mundo", "hola"]`: ambos tienen los mismos elementos, pero en posiciones diferentes. 

> Probá en orden en la consola las siguientes consultas: 
> 
>
> ``` javascript
ム listasIguales(["hola", "mundo"], ["mundo", "hola"])
```
>
> ``` javascript
ム listasIguales(["hola", "mundo"], ["hola", "todo", "el", "mundo"])
```
>
> ``` javascript
ム listasIguales(["hola"], ["hola", "mundo"])
```
>
> ``` javascript
ム listasIguales(["hola", "mundo"], ["hola", "mundo"])
```

> ¿Qué conclusiones podés sacar? :thought_balloon:
