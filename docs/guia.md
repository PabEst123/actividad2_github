4.1.1. Que es Git
Git es un sistema de control de versiones distribuido creado por Linus Torvalds en 2005.
Permite:

Registrar cambios en tus archivos a lo largo del tiempo.
Volver a cualquier version anterior.
Trabajar en ramas sin afectar el codigo principal.
Colaborar con otras personas de forma segura.

Cada desarrollador tiene una copia completa del proyecto en su ordenador, por lo que se puede trabajar sin conexion a internet.

4.1.2. Que es GitHub
GitHub es una plataforma en la nube que utiliza Git como motor.
Funciona como:

Un hosting de repositorios Git.
Un lugar para compartir codigo publicamente o de forma privada.
Una herramienta de colaboracion con pull requests, issues, proyectos, wikis, acciones, etc.

4.1.3. Diferencia entre repositorio local vs remoto
Aspecto: Repositorio Local
Ubicacion: En tu ordenador (carpeta .git)
Acceso: Siempre disponible sin internet
Proposito: Trabajar, hacer commits, crear ramas
Comandos clave: git commit, git branch, git checkout
Backup: Solo en tu maquina
Colaboracion: Solo tu
Aspecto: Repositorio Remoto
Ubicacion: En un servidor (GitHub, GitLab, Bitbucket)
Acceso: Necesita internet
Proposito: Compartir codigo, sincronizar con el equipo
Comandos clave: git push, git pull, git clone
Backup: Sirve como backup seguro
Colaboracion: Multiples personas pueden trabajar al mismo tiempo
Resumen rapido:
Local = tu copia de trabajo personal.
Remoto = la version compartida en la nube.
