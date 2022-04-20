# Punto de Venta

Punto de venta el cual tendrá opciones de compra de productos(Mercadería) y ventas(Facturación) de productos

# Entidades

## [Entidad (Cliente)]

- IdCliente(Pk)
- TipoDocumento
- NumeroDocumento
- Nombre
- Direccion
- Telefono
- Activo
- FechaRegistro

## [Entidad (Venta)]

- IdVenta(Pk)
- Codigo(Se genera por cada documento emitido automaticamente)
- IdTienda
- IdUsuario(Fk)
- IdCliente(Fk)
- IdTipoDocumento(Fk)
- CantidadProducto
- CantidadTotal
- TotalCosto
- ImporteRecibido
- ImporteCambio
- Estado
- FechaRegistro

## [Entidad (Detalle_Venta)]

- IdDetalleVenta(Pk)
- IdVenta(Fk)
- IdProducto(Fk)
- Cantidad
- PrecioUnidad
- ImporteTotal
- Estado
- FechaRegistro

## [Entidad (Tienda)]

- IdTienda(Pk)
- Nombre
- RUC
- Direccion
- Telefono
- Estado
- FechaRegistro


## [Entidad (Producto_Tienda)]

- IdProductoTienda(Pk)
- IdProducto(Fk)
- IdTienda(Fk)
- PrecioUnidadCompra
- PrecioUnidadVenta
- Stock
- Estado


## [Entidad (Producto)]

- IdProducto(Pk)
- Codigo
- ValorCodigo
- Nombre
- Descripcion
- IdCategoria
- Estado
- FechaRegistro
 
## [Entidad (Categoria)]

- IdCategoria(Pk)
- Descripcion
- Estado
- FechaRegistro

## [Entidad (Compra)]

- IdCompra(Pk)
- IdUsuario(Fk)
- IdProveedor(Fk)
- IdTienda(Fk)
- TotalCosto
- TipoComprobante
- Estado
- FechaRegistro

## [Entidad (Detalle Compra)]

- IdDetalleCompra(Pk)
- IdCompra(Fk)
- IdProducto(Fk)
- Cantidad
- PrecioUnitarioCompra
- PrecioUnitarioVenta
- TotalCosto
- Estado

## [Entidad (Proveedor)]

- IdProveedor(Pk)
- RUC
- RazonSocial
- Telefono
- Correo
- Direccion
- Estado
- FechaRegistro

## [Entidad (Usuario)]

- IdUsuario(Pk)
- Nombres
- Apellidos
- Correo
- Clave
- IdTienda(Fk)
- IdRol(Fk)
- Estado

## [Entidad (Rol)]

- IdRol(Pk)
- Descripcion
- Estado
- FechaRegistro

## [Entidad (Permisos)]
- IdPermisos(Pk)
- IdRol(Fk)
- IdSubMenu(Fk)(No necesario)
- Estado
- FechaRegistro

# Relaciones

- Una venta tiene un cliente
- Un cliente puede tener "N" ventas
- Una compra tiene un proveedor
- Un proveedor puede tener varias compras

# Funciones

- Crud Usuarios
- Crud Rol
- Crud Permisos
- Crud Clientes
- Crud Proveedor
- Crud Productos
- Crud Categorias
- Crud Tiendas
- Crear Compras
- Crear Ventas

# Pantallas

- Listado de usuarios.
- Listado de Rol.
- Listado de Permisos.
- Listado de Clientes.
- Listado de Productos.
- Listado de Categorias.
- Listado de Tiendas.
- Pantalla de creación de compras.
- Pantalla de creación de ventas.
- Pantalla de reportes de ventas y compras
