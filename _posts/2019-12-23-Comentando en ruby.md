---
published: true
---
## Escribiendo comentarios


Los comentarios en Ruby son de clase básica y de mucha importancia. Habrán veces en donde quieres explicar como funciona un código y para eso están los comentarios en Ruby. Los comentarios en de una sola línea comienzan con un **#**, Veamos un ejemplo en la consola de como funciona.




<div class="activity">
  💻
 En la terminal abajo, da click en <strong>ejecutar</strong>.  
</div> 

<iframe src="https://paiza.io/projects/e/h0n-c_fKwCLEHN_IrCIucA?theme=monokai" width="100%" height="500" scrolling="no" seamless="seamless"></iframe>


Notaste algo? No se imprimió nada, eso es porque cuando Ruby detecta el signo de **#**, reconoce que es un comentario y por lo cual no lo ejecuta. No es que no lo ignore, simplemente la sintaxis está escrita de esta forma. Ruby **nunca** ignora nada.

<div class="activity"> 
 💻
Ahora, en la terminal arriba elimina el signo de <strong>#</strong> y ejecuta el código.  
</div> 

<br>
<br>
<br>
<br>

### Comentario multiples

Ahora que tenemos eso muy entendido, ¿que pasaría si un día necesitas que escribir muchos comentarios a la vez? Bueno, tendrías que escribir por **cada** línea el signo de **#** pero eso es un poco raro y feo. Para eso Ruby nos trae **=begin** y **=end**

    =begin
        Puedo escribir lo que quiera entre begin y end sin necesidad de escribir mucho #
    =end
    
<div class="activity"> 
 💻
En la terminal abajo elimina los signos de <strong>#</strong> y escribe <strong>=begin</strong> y <strong>=end</strong> entre el texto, no olvides ejecutar el código.
</div> 
    
 <iframe src="https://paiza.io/projects/e/NoxeT_FjKYwKPYtQNa7mrQ?theme=monokai" width="100%" height="500" scrolling="no" seamless="seamless"></iframe>
