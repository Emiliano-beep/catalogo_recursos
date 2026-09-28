¿Qué ventaja tiene registrar las dependencias del proyecto en
requirements.txt en lugar de compartir la carpeta .venv? 
Registrar las dependencias en requirements.txt garantiza que el proyecto sea portable entre diferentes sistemas operativos y computadoras 
(ya que la carpeta .venv contiene archivos binarios y rutas absolutas que solo funcionan en la máquina donde se creó), reduce el peso del proyecto de cientos de megabytes a un archivo de texto de solo unos kilobytes, y evita saturar los repositorios de código como Git.