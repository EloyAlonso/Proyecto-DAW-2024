# FASE DE IMPLANTACIÓN

- [FASE DE IMPLANTACIÓN](#fase-de-implantación)
  - [1- Manual técnico](#1--manual-técnico)
    - [1.1- Instalación](#11--instalación)
    - [1.2- Administración do sistema](#12--administración-do-sistema)
  - [2- Manual de usuario](#2--manual-de-usuario)
  - [3- Melloras futuras](#3--melloras-futuras)

## 1- Manual técnico

### 1.1- Instalación

> *EXPLICACIÓN:* Neste apartado describiranse todos os pasos necesarios para que calquera persoa poida descargar o código do proxecto e continuar o seu desenvolvemento.
>
> Como:
> 
> - Requirimentos de hardware, servidores na nube, etc.
> - Software necesario: servidores (Exemplo servidor Web), software externo co que interaciona a nosa aplicación, contenedores, etc.
> - Carga inicial de datos na base de datos. Migración de datos xa existentes noutros formatos.
> - Usuarios da aplicación.
> - Diagrama final de despregue (se hai variacións con respecto ó realizado na anterior fase).

Para el despliegue de la web se puede optar por 2 diferentes formas: Desde windows o desde linux.

Yo personalmente despliego el proyecto desde WSL (Windows Subsistem Linux) donde meto el repositorio de la web en mi distro ya configurada con docker ya instalado internamente.
Recomiendo ver este vídeo si quieres instalar docker dentro de WSL en vez de usar Docker Desktop ya que relantizará mucho la página:
[Instalar Docker en WSL](https://www.youtube.com/watch?v=cv7Iyohhmo4)

En el caso de que quieras tener el repositorio en el sistema operativo Windows simplemente tienes que descargar Docker Desktop, pero la carga de la página será mucho más lenta.

Para el despliegue hay 2 scripts dependiendo del sistema operativo desde el que se quiera lanzar: build.sh (para linux y wsl) y windows.ps1

Tan solo hay que ejecutarlos y en unos minutos estará desplegada la web con su base de datos importada y funcionando.

Tener en cuenta que a lo mejor build.sh no tiene permisos para ser ejecutable así que en caso de que no se pueda ejecutar hay que darle permisos de ejecución "chmod +x ./build.sh"

Y en cuanto al script de Windows puede suceder que powershell no tenga habilitada la ejecución de scripts así que recomiendo usar este comando: 

### 1.2- Administración do sistema

> *EXPLICACIÓN:* Neste apartado indicarase información relativa á administración do sistema, é dicir, tarefas que se deberán realizar unha vez que o sistema estea funcionando.
>
> Como:
> 
> - Copias de seguridade do sistema.
> - Copias de seguridade da base de datos.
> - Xestión de usuarios.
> - Xestión seguridade.
> - Xestión de incidencias, que poden ser de dous tipos: de sistema (accesos non autorizados á BD, etc) ou de fallos no software.
>
> No caso de que sexan precisas.

## 2- Manual de usuario

> *EXPLICACIÓN:* Neste apartado fara
>
> - Indicar se será necesario formar ós usuarios. En caso afirmativo planificar.
> - Manual de usuario, FAQ ou outro xeito que sexa o máis adecuado para que os usuarios saiban usar a nosa aplicación informática.
>
> Todo esto se a aplicación require de manual de usuario.

## 3- Melloras futuras

> *EXPLICACIÓN:* Neste apartado incluiranse as posibilidades de mellora da aplicación no futuro.
