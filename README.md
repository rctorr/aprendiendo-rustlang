# Aprendiendo Rust-Lang
Prácticas realizadas para aprender y ensayar algunas características de Rust-Lang

## Preparación de herramientas
Para poder realizar las prácticas es sugerible contar con Rust instalado, en el sitio oficial existen descargas para almenos los principales sistemas operativos https://www.rust-lang.org/en-US/downloads.html

No se en este momento si existan o se pueda compilar ejecutables para por ejemplo una Raspberry Pi, Arduino o plataformas distintas a las Intel PC compatibles (incluyendo Macs).

### Instalación en RHEL 7.2
Me imagino que la instalación tiene que ser imilar en CentOS 7, así como en Fedora, pero ha sido muy simple, sólo ejecutar el siguiente comando desde la terminal:
```console
# yum install rust
...
# exit
$ rustc --version
1.13.0
$
```
La versión 1.13.0 es la versión recomendada, así que ya podemos seguir ;)

### Instalación en Linuxmint 17.1 Rebecca
Contrario a lo que he supuesto, pensé que Rust se podría instalar con un simple `apt-get install` pero no ha sido así, al realizar la búsqueda de un paquete el resultado fué nulo y al buscar en google para instalar Rust en LinuxMint 17.1 no ha aparecido nada contundente, aunque sí algunos problemas con algunas librerías.

Por lo tanto toca hacer la instalación usando el comando sugerido por si sitio de Rust...
```console
$ curl -sSf https://static.rust-lang.org/rustup.sh | sh
...
    Rust is ready to roll.
    
$ rustc --version
rustc 1.13.0 (.... 2016-11-07)
$
```
La instalación se realizó de forma rápida y también es la versión 1.13.0, así que todo bien a codear ;)

## Prácticas
Para tener un poco más ordenados los ejemplo, voy a dividir en dos categorías, las `mini-practicas` donde cada archivo de código fuente por lo general muestra como usar o se enfoca en mostrar como usar alguna funcionalidad del lengujes Rust, también están las `super-practicas` donde habrá ejemplos de como resolver alguna problemática donde se involucran algoritmos, librerías o alguna otra herramienta que ayude a resolver el problema.

- mini-practicas
- super-practicas

## Recursos
- https://www.rust-lang.org
- https://doc.rust-lang.org/stable/book
- http://rustbyexample.com
