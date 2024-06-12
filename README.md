# ChatGPT para los pobres

Este proyecto es un chatbot impulsado por inteligencia artificial que se ejecuta completamente en el navegador web, sin necesidad de un backend ni APIs externas. Utiliza Web Workers para mejorar el rendimiento y la experiencia del usuario al procesar las solicitudes de manera eficiente en segundo plano.

## Características

- **Funcionamiento en el navegador**: No requiere conexión a Internet ni servidores externos para funcionar, lo que garantiza la privacidad y la seguridad de las conversaciones.
  
- **Integración sencilla**: Puede integrarse fácilmente en cualquier sitio web mediante la inclusión de un script en el HTML.
  
- **Optimización de rendimiento**: Utiliza Web Workers para realizar operaciones intensivas de computación de manera eficiente, sin bloquear la interfaz de usuario.

## Tecnologías Utilizadas

- **JavaScript**: Lenguaje principal para la implementación del chatbot en el lado del cliente.
  
- **Web Workers**: Utilizados para ejecutar el motor de inteligencia artificial (`MLCEngine`) en un entorno multihilo y mejorar la eficiencia del procesamiento.

- **MLCEngine**: Motor de inteligencia artificial proporcionado por `@mlc-ai/web-llm`, optimizado para ejecutarse en navegadores modernos.

## Instalación

Para ejecutar el ChatGPT en tu entorno local, sigue estos pasos:

1. Clona este repositorio:

   ```bash
   git clone https://github.com/tu-usuario/nombre-del-repositorio.git
