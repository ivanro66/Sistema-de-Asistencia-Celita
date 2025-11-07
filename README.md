📄 SISTEMA DE ASISTENCIA CELITA
Versión 1.0 | Desarrollado por T.S.U. Iván Romero
Dirección de Tecnología e Informática
Fundación Regional El Niño Simón Apure

🔧 REQUISITOS:
- Sistema operativo: Windows 10 o superior
- No requiere instalación de Python
- No requiere conexión a internet

🚀 INSTRUCCIONES DE USO:
1. Abrir la carpeta "SistemaAsistencia"
2. Ejecutar el archivo "main.exe" con doble clic
3. Iniciar sesión como "admin" o "soporte" (según configuración)
4. Usar el sistema normalmente: registrar asistencia, generar reportes, etc.

📁 IMPORTANTE:
- No borrar las carpetas "recursos", "base_datos", ni los archivos .csv
- Si el sistema no abre, verificar que el antivirus no esté bloqueando el ejecutable

💬 SOPORTE:
Para asistencia técnica, contactar a la Dirección de Tecnología
ivanrodeveloper@gmail.com



Sistema institucional desarrollado para la Fundación Regional El Niño Simón Apure, con el objetivo de registrar asistencia en las Casas de los Niños del Estado Apure.

## 🛠️ Tecnologías
- Python 3
- SQLite
- Tkinter
- PyInstaller

## 📁 Estructura
- `main.py`: archivo principal
- `base_datos/`: contiene la base de datos SQLite
- `recursos/`: imágenes y logos institucionales
- `interfaz_grafica/`: módulos visuales
- `modules/`: lógica del sistema

## 🚀 Empaquetado
El sistema puede ser convertido en `.exe` usando PyInstaller:

```bash
pyinstaller --onefile --noconsole ^
--add-data "recursos;recursos" ^
--add-data "base_datos;base_datos" ^
--add-data "interfaz_grafica;interfaz_grafica" ^
--add-data "modulos;modulos" ^
main.py
