# Catalogo de productos
Aplicacion que permite llevar el control de un catalogo de productos actualizable. Además se desea llevar el control de los productos que estan agotados segun el stock de inventario por bodega.

Un producto puede tener dos estados:
<li>Mientras haya existencia el producto estara visualizado en pantalla.</li>
<li>Cuando el producto este agotado, es decir con existencia igual a cero, este no se mostrara en el catalogo.</li>

# Entidades

## Producto
<ul>
<li>Id</li>
<li>Producto</li>
<li>Imagen</li>
<li>Stock</li>

## Bodega
<li>Id</li>
<li>Bodega</li>
<li>Detalle</li>

## Usuario
<li>Id</li>
<li>Nombre</li>
<li>correo</li>

# Relaciones
<li>Un producto tiene una bodega</li>
<li>Una bodega tiene asignados muchos productos</li>
<li>Un usuario modifica el estock de uno o mas productos</li>

# Funciones
<li>Crear usuario</li>
<li>Editar usuario</li>
<li>Autenticar usuario</li>
<li>Crear producto</li>
<li>Editar producto</li>
<li>Borrar Producto</li>
<li>Buscar producto</li>
<li>Modificar estado de producto</li>

# Pantallas
<li>Catalogo productos</li>
<li>Detalle productos</li>
<li>Login usuario</li>
<li>Administrar Catalogo</li>
<li>Crear/Editar producto</li>
<li>Crear/Editar Usuario</li>


  


