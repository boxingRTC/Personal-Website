1. The page has a logical tab order
La pagina sigue un orden visual correcto al tabular. 

2. Interactive controls are keyboard focusable
La página no dispone de elementos seleccionables, el único caso es al reducir la resolución, y se puede seleccionar hacia que lugar de la página 
se quiere ir a través del tabulador, las flechas del teclado y el enter para confirmar. 

3. Interactive elements indicate their purpose and state
Al selecionar con tabulador uno de los elementos, se indica con un borde negro a su alrededor.

4. The user's focus is directed to new content added to the page
La página no tiene como objetivo actualizarse de forma continuada, por tanto no es necesario dirigir el focus del usuario automáticamente,
es mas 

5. User focus is not accidentally trapped in a region
Se puede navegar con tab y shift+tab en el menú, pero dentro de la propia página no salta correctamente entre secciones. Se podria solucionar identificando cada sección de forma que sea identificable con un tabulador. 

6. Custom controls have associated labels
Cada tab tiene su nombre, cuando tabeas no se selecciona en blanco, se indica el nombre del elemento seleccionado. 

7. Custom controls have ARIA roles
Cada control personalizado tiene que tener su correspondiente rol. Por ejemplo un checkbox tiene que tener: role="checkbox" y aria-checked="true|false". En caso de esta página, se determina un rol de navegación en el footer y en el navbar. (Añadidos manualmente.)

8. Visual order on the page follows DOM order
El orden que siguen los tabs es en orden. A la hora de tabular se sigue el orden de arriba-abajo, en el caso de la navegación del navbar y de izquierda a derecha en el caso de los iconos del footer. 

9. Offscreen content is hidden from assistive technology
No hay contenido que deba ser marcado como "hidden", es decir todos los elementos que se leen en un screenreader leen apropiadamente el texto. Pues no hay elementos sobrantes que a la hora de un screenreader sean leidos. 

10. HTML5 landmark elements are used to improve navigation
La página muestra el formato apropiado, encapsulando correctamente los elementos correspondientes. 

