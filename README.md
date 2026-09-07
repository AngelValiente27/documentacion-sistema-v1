# Sistema de Gestión de Inventario - TechStore

## 1. Descripción del Proyecto
TechStore es un sistema de ventas diseñado para gestionar productos, inventario y ventas de manera rápida y organizada.
Permite llevar un control eficiente del stock, registrar ventas y facilitar la gestión de clientes y comprobantes de pago.

## 2. Requisitos del Sistema
Crea una lista de tareas (checklists) con los siguientes requisitos:
- [x] Python 3.10 o superior instalado
- [x] Base de Datos MySQL configurada
- [x] Documentación técnica completada

## 3. Módulos del Sistema
Crea una tabla en Markdown con la siguiente estructura:

| Módulo | Descripción | Estado |
|---|---|---|
| Autenticación | Control de acceso y roles de usuario | Completado |
| Inventario | Registro y conteo de productos | En Proceso |
| Facturación | Generación de comprobantes de pago | Pendiente |

## 4. Ejemplo de Código Fuente
Inserta un bloque de código en Python formateado adecuadamente que contenga el siguiente algoritmo básico:

```python
def verificar_stock(cantidad):
    if cantidad > 0:
        return "Producto Disponible"
    else:
        return "Sin Stock"
