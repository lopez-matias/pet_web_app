# Vetora — Prototipo veterinaria

Demo visual navegable para presentar el concepto de una aplicación web de veterinaria.

## Incluye

### Vista cliente
- Inicio
- Tienda y filtros por categoría
- Carrito simulado
- Agenda con selección de servicio, día y horario
- Confirmación de reserva + ejemplo de email
- Mis mascotas

### Vista administrador
- Dashboard con KPIs
- Pedidos con flujo Pendiente → Preparado → Notificado → Entregado
- Simulación de email para retiro
- Productos, stock, precios y alta de producto
- Agenda semanal
- Acceso a ficha clínica simulado

## Ejecutar localmente

No requiere instalación.

1. Abrir `index.html` en un navegador, o
2. Ejecutar un servidor local:

```bash
python -m http.server 8080
```

Luego abrir `http://localhost:8080`.

## Publicar en Vercel

Este proyecto es estático y puede desplegarse directamente.

1. Crear un repositorio en GitHub.
2. Subir estos archivos a la raíz del repositorio.
3. En Vercel: Add New → Project → importar repositorio.
4. Framework Preset: `Other`.
5. Build Command: vacío.
6. Output Directory: `.`.
7. Deploy.

## Importante

Es un prototipo. Los datos, clientes, mascotas, pedidos, métricas y correos son ficticios y no existe backend ni persistencia real.
# pet_web_app
