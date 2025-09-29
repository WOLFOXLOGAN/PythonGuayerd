Link de visualización DOCUMENTACION.md en github: [github](https://github.com/WOLFOXLOGAN/PythonGuayerd/blob/main/DOCUMENTACION.md)
# FUNDAMENTOS DE IA ![Static Badge](https://img.shields.io/badge/Inteligencia-Artificial-cyan)
## Camada 25 
### Parte de la Primera Entrega

1. Crea una **carpeta en tu PC**  "Tu nombre - Proyecto Aurelion"   
    >OK
2. **Conecta** dicha carpeta a VS Code.
    >OK
3. Dentro, crea el archivo **DOCUMENTACION.md**.
    >OK
4. Desccribe el problema que quieres resolver o que te gustaria analizar.
    >Me gustaria analizar la tendencia de productos mas solicitados por los clientes para tener siempre actualizado el stock y verificar porque hay productos con menos ventas.
5. Describe **estructura, tipos y escala** de la BD.

    Tabla Clientes:
    >|Estructura     |Tipo   |Escala     |  
    >|---------------|-------|-----------|
    >|id_cliente     |int    |ordinal    |
    >|nombre_cliente |str    |nominal    |
    >|email          |str    |nominal    |
    >|Ciudad         |str    |nominal    |
    >|fecha_alta     |str    |intervalo  |
    Tabla Productos
    >|Estructura     |Tipo   |Escala     |  
    >|---------------|-------|-----------|
    >|id_producto     |int    |ordinal   |
    >|nombre_producto |str    |nominal   |
    >|categoria       |str    |nominal   |
    >|precio_unitario |float  |razón     |
    Tabla Ventas
    >|Estructura     |Tipo   |Escala     |  
    >|---------------|-------|-----------|
    >|id_venta       |int    |ordinal   |
    >|fecha          |str    |intervalo  |
    >|id_cliente     |int    |ordinal    |
    >|nombre_cliente |str    |nominal    |
    >|email          |str    |nominal    |
    >|medio_pago     |str    |nominal    |
    Tabla "Detalle_ventas"
    >|Estructura     |Tipo   |Escala     |  
    >|---------------|-------|-----------|
    >|id_venta        |int    |ordinal   |
    >|id_producto     |int    |ordinal   |
    >|nombre_producto |str    |nominal   |
    >|cantidad        |int    |razón     |
    >|precio_unitario |float  |razón     |
    >|Importe         |float  |razón     |
