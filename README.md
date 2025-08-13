# Concurso de rustfmt 📝

Este es el repositorio de Github orientado al concurso de rustfmt de la comunidad de [Discord de RustLangES](https://discord.rustlang-es.org/).   
En este repositorio se recibirán en formato de Pull Requests las postulaciones del concurso, ¡mucha suerte!

## ¿De qué trata el concurso? ❓
rustfmt es la herramienta de formato de Rust, esta misma automatiza y unifica la configuración del formato del código dentro de los proyectos de Rust, y es utilizada por los editores de código y Cargo.   
El concurso consiste en elaborar el archivo de configuración de rustfmt que provea el peor formato de código posible, el Staff de RustLangES juzgará las distintas postulaciones y determinará un ganador, al cual se le dará como premio la membresía de Discord nitro de 1 año.   

## Reglas 🚩
Estableceremos algunas reglas que no serán estrictas pero sí afectan fuertemente el juicio:
- Se deben aplicar varias reglas de formato, debe haber algo de empeño
- No se debe abusar de reglas de formato que simplemente proveen espaciado en el código
- El formato debe estar activado
- Es válido usar todas las opciones no estables de la configuración
- Haber interactuado en nuestra comunidad de Discord

## Cómo participar ❓
Primero debes hacer un Fork de este repositorio, dentro del mismo se encuentra el archivo `rustfmt.toml` el cual contiene un ejemplo basico de un archivo de configuracion de rustfmt, se deberán agregar, quitar, o modificar las distintas opciones de configuración con el fin de realizar el peor formato de código.   
Luego, se debe aplicar el formato, esto suele suceder de forma automática aunque también se puede realizar manualmente con el comando `cargo fmt`, finalmente se debe publicar la postulación como una Pull Request a este mismo repositorio, indicando en la descripción de la Pull Request el nombre de usuario y apodo de Discord con el que los identificamos dentro de nuestra comunidad adjuntando pruebas de haber interactuado con dentro de la comunidad (alguna captura de mensajes, colaboracion en GitHub o participacion en los canales de Voz).   

## Recursos 📚
Como recursos, les dejamos la documentación de la configuración de rustfmt, como también el repo de github con el código fuente, para que puedan conocer las distintas configuraciones que se pueden aplicar:
- [rustfmt docs](https://rust-lang.github.io/rustfmt/?version=v1.8.0)
- [rustfmt source](https://github.com/rust-lang/rustfmt)
