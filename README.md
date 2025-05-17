
 ## Tienda de Botas de Futbol

### Modelo de datos
- Marca: id, nombre, pais
- Bota: id, modelo, talla, precio, stock, marca

### Reparto de tareas
- Yo:
  - Implementacion de MarcaDAO
  - Funcionalidad: crear marcas y listar sus botas (usando BotaDAO)
- Yo tambien:
  - Implementacion de BotaDAO
  - Funcionalidad: registrar nuevas botas (usando MarcaDAO)

### Metodos utilizados del compañero
- Yo use: BotaDAO.obtenerPorMarca(marcaId)
- Yo tambien use: MarcaDAO.obtenerPorId(id)


