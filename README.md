# Configurando Git por primera vez:

- git --version
- git config --global user.name "Jonathan MirCha"
- git config --global user.email jonmircha@gmail.com
- git config --global user.ui true
- git config --global init.defaultBranch main
- git config --list

asignando visual studio code como editor de configuración de git

- git config --global core.editor "code --wait"
- git config --global -e

para estandarizar los saltos de línea en windows

- git config --global core.autocrlf true

para estandarizar los saltos de línea en linux/mac

- git config --global core.autocrlf input

ver todas las opciones de la configuración en la terminal

- git config -h

ver todas las opciones de la configuración en el navegador

- git help config

# Inicializar Git en un directorio local:

1. mkdir carpeta
1. cd carpeta
1. touch README.md
1. touch .gitignore
1. git init
1. code .

# Flujo básico:
