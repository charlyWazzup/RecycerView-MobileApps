### ¿Cómo funciona el RecyclerView?

El widget RecyclerView es una de las novedades más importante que ha recibido Android en los últimos tiempos desde el punto de vista del desarrollador ya que permite reemplazar widgets fundamentales como ListView y GridView por “algo mejor” y más potente. En pocas palabras, es un contenedor de elementos en forma de lista al igual que la clase ListView. 

Aunque ambos tienen la misma función, este nuevo elemento permite “reciclar” los ítems que ya no son visibles por el usuario debido al scrolling, por lo que es ideal para proyectos que manejan grandes volúmenes de ítems que se actualizan constantemente, limitando la visibilidad de elementos. Adicionalmente permite configurar una serie de animaciones para la eliminación, desplazamiento y creación de nuevos elementos en tiempo real.

La creación y administración de un RecyclerView es similar a la de un ListView. Se necesita una fuente de datos que provea la información lógica de cada elemento y un adaptador que los lea, interprete e infle. Pero también es necesario un nuevo elemento llamado LayoutManager.

El LayoutManager es el encargado de añadir y reusar los views en el recycler. Su función es calcular las posiciones fuera del foco del usuario y así reemplazar el contenido de un ítem fuera del volumen visual por el contenido de otro. Esto reduce los tiempos de ejecución.

La simplicidad y modularidad convierten a RecyclerView en un poderoso componente porque permite construir cualquier interfaz gráfica en la que se requiera mostrar un listado de datos sin tener que limitarnos a lo ofrecido por ListView o GridView.

Aunque tiene la ventaja de soportar multitud de animaciones muy eficientes para cuando creamos, editamos y eliminamos un elemento, carece de otras funcionalidades básicas.

No tiene un método para implementar empty views o lo que es lo mismo, imágenes/texto para cuando no hay ningún elemento en la lista. No dispone de un método que recoja la pulsación del elemento. 




