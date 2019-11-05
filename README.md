# visitas-python
Desarrollo en Python para automatizar la visita de videos en youtube.

## Características

* Multi-threaded.
* Soporta multiples URL
* Soporta ChromeDriver y GeckoDriver.
* Modo Headless.
* Modo de inicio lento para máquinas viejas. 
* Se puede configurar la duración de la visita. 
* Se puede cambiar de IP y de Agente de visualización.
* Spoofing.
* Modo Debug.

## Forma de uso

`python main.py ARGUMENTOS`

## Documentación

### Argumentos Requeridos

| Argumento      | Descripción                  |
| :------------- | :--------------------------- |
| -u, --url URL  | URL del video.               |
| -u, --url PATH | PATH del archivo con las URL.|

### Argumentos Opcionales

| Argumento                     | Descripción                              |Valor por defecto               |
| :---------------------------- | :--------------------------------------- | :----------------------------- |
| -h, --ayuda                   | Muesstra la ayuda                        |                                |
| -t, --threads N               | Configura el número de threads.          | 15                             |
| -D, --driver {chrome,firefox} | Configura el webdriver.                  | chrome                         |
| -H, --headless                | activa el modo headless                  | False                          |
| -s, --slow-start              | Activa el modo Inicio Lento              | False                          |
| -du, --duración N             | Define la duración de la visita.         | Duración total del video.      |
| -p, --proxies PATH            | Define el archivo con los proxies.       | Lista de proxies.              |
| -U, --user-agent AGENT        | Define el agente a usar.                 | Se define de forma aleatoria   |
| -U, --user-agent PATH         | Define el PATH del archivo con agentes.  |                                |
| -R, --referencia REFERER      | Define una referencia.                   | https://google.com             |
| -R, --referencia PATH         | Define el archivo con referencias.       |                                |
| -d, --debug                   | Activa el modo debug                     | False                          |
| -r, --actualización N         | Define el tiempo de actualización.       | 1.0                            |

