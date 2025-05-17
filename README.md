
 ## Tienda de Botas de Futbol

### Modelo de datos
- Marca: id, nombre, pais
- Bota: id, modelo, talla, precio, stock, marca

### Reparto de tareas
- Yo:
  - Implementacion de MarcaDao
  - Funcionalidad: crear marcas y listar sus botas (usando BotaDao)
- Yo tambien:
  - Implementacion de BotaDao
  - Funcionalidad: registrar nuevas botas (usando MarcaDao)

### Metodos utilizados
- Botas: BotaDao.obtenerPorMarca(marcaId)
- Marcas: MarcaDao.obtenerPorId(id)

(los dos los hago yo no encontre pareja)

