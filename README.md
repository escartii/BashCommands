<div align="center">

# Bash Commands

</div>

¡Bienvenido a NuevoComandos! Este es un proyecto open source dedicado a agregar nuevos comandos útiles a tu terminal, para mejorar tu flujo de trabajo y productividad.

## ¿Por qué este proyecto?

Empecé este proyecto con la idea de simplificar y mejorar la experiencia del usuario en la línea de comandos. A menudo nos encontramos repitiendo tareas simples pero tediosas, y a veces nos gustaría tener comandos específicos que no vienen de serie en nuestros sistemas. Este proyecto busca llenar ese vacío proporcionando una colección de comandos útiles y prácticos que pueden ser fácilmente añadidos y utilizados por cualquiera.

## ¿Cómo contribuir?

¡Estoy emocionado de recibir contribuciones de la comunidad! Si tienes ideas para nuevos comandos, mejoras para los existentes, o simplemente quieres ayudar a mejorar la documentación, ¡tu contribución es bienvenida!

Aquí hay algunas formas en las que puedes contribuir:

- **Añadir nuevos comandos:** Si tienes un comando que encuentras útil y crees que otros podrían beneficiarse de él, ¡no dudes en agregarlo! Asegúrate de seguir las mejores prácticas de codificación y documentación.

- **Mejorar comandos existentes:** Si encuentras algún comando que podría ser más eficiente, más claro en su funcionamiento o simplemente mejorado de alguna manera, ¡adelante y haz los cambios necesarios!

- **Reportar problemas:** Si encuentras algún problema o bug en un comando existente, por favor abre un issue detallando el problema. Intenta proporcionar toda la información relevante para que podamos reproducir y solucionar el problema rápidamente.

## Cómo añadir estos comandos a tu sistema

Para añadir estos comandos a tu sistema y empezar a usarlos, sigue estos sencillos pasos:

1. **Clona el repositorio:** Primero, clona este repositorio a tu máquina local utilizando el siguiente comando:

```bash
git clone https://github.com/tunombredeusuario/BashCommands.git
```

2. **Abre tu editor favorito..**
```bash
vim .bashrc
```

3. **Agrega tu comando:**

```bash
alias mkcd='function _mkcd() { mkdir -p "$1" && cd "$1"; }; _mkcd'
```

```bash
source ~/.bashrc
```

5.**Ejemplo de uso:**

```bash
mkcd nuevo_directorio
```



