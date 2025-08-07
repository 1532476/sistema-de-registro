# 📦 Informe de Abastecimiento - Agosto 2025

## 🧾 Resumen

### MODIFICACION 3

Este documento presenta un resumen del estado actual del abastecimiento en la **Administración Central**, incluyendo productos clave, cantidades disponibles, precios y observaciones generales.
### MODIFICACION 4

Este texto es un texto de prueba, para probar *negrita* **cursiva** y ***ambos***
---

## 📋 Productos en Inventario

| Producto       | Código | Precio Unitario | Cantidad Disponible |
|----------------|--------|------------------|----------------------|
| Papel Bond     | PB001  | $2.50            | 1200 unidades        |
| Toner HP 85A   | THP85A | $45.00           | 35 unidades          |
| Carpetas A-Z   | CAZ01  | $1.20            | 500 unidades         |

---

## ✅ Tareas Realizadas

1. Revisión de inventario físico.
2. Actualización en el sistema SAP.
3. Solicitud de cotizaciones a proveedores.
4. Envío de reporte al área financiera.

---

## 📌 Observaciones

> Se detectó una baja en el stock de toner HP 85A. Se recomienda realizar una orden de compra antes del 10 de agosto.

---

## 🔗 Enlaces Útiles

- Sistema SAP
- [Catálogo de proveedores](https# 🧠 Código de ejemplo para análisis

```python
# Calcular el valor total del inventario
productos = {
    "Papel Bond": {"precio": 2.5, "cantidad": 1200},
    "Toner HP 85A": {"precio": 45.0, "cantidad": 35},
    "Carpetas A-Z": {"precio": 1.2, "cantidad": 500}
}

total = sum(p["precio"] * p["cantidad"] for p in productos.values())
print(f"Valor total del inventario: ${total}")
