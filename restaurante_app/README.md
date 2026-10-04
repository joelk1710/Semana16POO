# Restaurante App - Semana 16 (Manejo Avanzado de Eventos)

## Propósito de la Actividad
Evolución de la aplicación gráfica aplicando conceptos fundamentales de manejo de eventos en Tkinter. Se incorpora la gestión completa de usuarios con diferenciación de roles (**Administrador**, **Empleado**, **Cliente**), haciendo uso intensivo de `bind()`, eventos virtuales como `<<TreeviewSelect>>` y `<<ComboboxSelected>>`, y atajos de teclado como `<Return>` y `<Escape>`, manteniendo la arquitectura modular y la persistencia en archivos JSON.

## Estructura del Proyecto
- `datos/`: Archivos JSON de persistencia (`productos.json`, `usuarios.json`, `ventas.json`).
- `modelos/`: Clases de entidad (`producto.py`, `usuario.py`, `venta.py`).
- `servicios/`: Capa de negocio y persistencia (`archivo_servicio.py`, `restaurante_servicio.py`).
- `ui/`: Interfaces gráficas (`login_view.py`, `main_view.py`).
- `assets/`: Recursos gráficos obligatorios, incluyendo el logotipo (`logo.png`).
- `main.py`: Punto de entrada del sistema.

## Instrucciones de Ejecución
```bash
python main.py
Credenciales de prueba:

Administrador: admin / 123

Empleado: cajero1 / 456