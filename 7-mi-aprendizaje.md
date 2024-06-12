# Comparación de Conocimientos y Aprendizajes Logrados
## Antes de la Práctica:
- Antes de realizar la práctica. No estaba familiarizado con la configuración avanzada de Docker, como la limitación de recursos, la creación de Dockerfiles detallados y la gestión de contenedores en diferentes entornos de ejecución.

## Después de la Práctica:
- Después de completar la práctica, he adquirido una comprensión más profunda y avanzada de Docker, lo cual es beneficioso para mi formación profesional en varios aspectos:

### Limitación de Recursos:

- Aprendí a limitar los recursos del sistema (CPU, memoria) que un contenedor puede utilizar, lo que es crucial para prevenir abusos, aislar contenedores y gestionar eficientemente los recursos en entornos de producción.
Creación y Configuración de Dockerfiles:

- Ahora puedo crear Dockerfiles personalizados para configurar entornos de contenedores específicos, instalando software necesario, copiando archivos y configurando el entorno de ejecución de manera precisa.
Gestión de Memoria:

- Comprendí cómo definir límites de memoria y memoria swap para los contenedores, lo que ayuda a asegurar que los contenedores no consuman más recursos de los necesarios y que el sistema permanezca estable y eficiente.
Uso de PowerShell y Permisos de Administrador:

- Experimenté y resolví problemas relacionados con permisos al construir imágenes Docker. Aprendí que en algunos casos es necesario usar PowerShell en lugar de CMD y ejecutar comandos con permisos de administrador para evitar errores.
  
### Health Checks y Políticas de Reinicio:

- Adquirí conocimientos sobre cómo implementar health checks en Docker para monitorizar el estado de los contenedores y configurar políticas de reinicio para asegurar que los contenedores se mantengan operativos.
  
### Problema Solucionado:
Un problema significativo que encontré fue al intentar crear una imagen con un Dockerfile en CMD, donde se requerían permisos de administrador y no se podía completar el proceso correctamente. La solución que encontré fue ejecutar el comando en PowerShell con permisos de administrador, lo que resolvió el problema y permitió construir la imagen sin inconvenientes. Esta experiencia me enseñó la importancia de tener en cuenta los entornos y permisos necesarios al trabajar con Docker, especialmente en sistemas Windows.
