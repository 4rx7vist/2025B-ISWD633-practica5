# COMPLETAR  
Comparando sus conocimientos antes de hacer la práctica con sus conocimientos después de hacer la tarea, explicar los principales aprendizajes logrados para beneficio de su formación profesional.  
Si solucionó un problema presentado al realizar la práctica también se debe documentar.

## Mi Aprendizaje 
Comprendía los conceptos básicos de contenedores y la idea general de orquestación, pero carecía de experiencia práctica en cómo integrar múltiples servicios de manera efectiva. Sabía que Docker Compose permitía gestionar aplicaciones multi-contenedor, pero no había implementado nunca configuraciones complejas con dependencias entre servicios, health checks o políticas de reinicio. Mi entendimiento se limitaba a ejemplos simples sin la profundidad necesaria para aplicaciones reales.

Uno de los aprendizajes más significativos fue comprender la gestión de dependencias entre servicios. Al configurar WordPress para que dependiera de MySQL con la condición service_healthy, entendí la importancia de coordinar el inicio de servicios interconectados. Este conocimiento es crucial para mi formación profesional, ya que en entornos de producción es esencial que los servicios se inicien en el orden correcto y solo cuando sus dependencias estén realmente disponibles, evitando así errores de conexión y mejorando la confiabilidad del sistema. Igualmente, el manejo de volúmenes y persistencia de datos fue un área donde gané considerable experiencia práctica para integrarlo en el archivo de compose en postgres. 

Este conocimiento es fundamental para cualquier implementación profesional donde la pérdida de datos es inaceptable o pueda escalar a un nivel de persistencia en grandes sistemas, y sobre todo compose de docker a mi consideracion lo plasmo como una documentacion de configuracion ante alguna ocacionalidad a futuro para que se pueda modificar y permita escalar en un sistema. 
