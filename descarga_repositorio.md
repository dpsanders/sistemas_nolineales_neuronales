# Descargar el repositorio del curso

- Para descargar Julia, revisa los [recursos_Julia.md](https://github.com/dpsanders/sistemas_nolineales_neuronales/blob/master/recursos_Julia.md)

## Si Julia ya está instalado en tu computadora

- Abre la terminal (no la terminal de Julia, sino la usual) y úbicate en el directorio donde quieras que se descargue el repositorio;
- Copia y pega la siguiente línea:
  ```
  git clone https://github.com/dpsanders/sistemas_nolineales_neuronales.git
  ```
- Si después de dar "enter", la terminal no reconoce `git`, entonces hay que instalar este último (ve un poco más abajo);
- Si el repositorio se descargó correctamente, entonces es **sumamente** recomendable que se haga una copia de los notebooks donde hay que trabajar.
Esto es para evitar que cada vez que se actualice el repositorio, tu trabajo no se sobreescriba y corras el riesgo de perderlo :(;
- Abre `jupyter notebook` y ponte a trabajar (si no recuerdas como abrir el notebook, ve a [recursos_Julia.md](https://github.com/dpsanders/sistemas_nolineales_neuronales/blob/master/recursos_Julia.md)).

### Instalar `git`
- Si trabajas en Linux, un simple `sudo apt-get install git` basta;
- En Mac OS, un `brew install git` si tienes `homebrew` instalado o `git --version`;
- Para Windows, aunque también para Mac OS, puedes bajar los ejecutables desde [la página de git](https://git-scm.com/downloads).

## Si Julia no está instalado en tu computadora

- Entra a http://next.juliabox.com y regístrate;
- Una vez que estés dentro, en la barra superior da click en la opción "Git";
- Aparecerá una ventana llamada "Sync";
- Pega en la opción "Git Clone URL" la siguiente línea
  "https://github.com/dpsanders/sistemas_nolineales_neuronales.git";
- Las opciones "Branch" y "Folder" se deberían de llenar automáticamente con
  "master" y "sistemas_nolineales_neuronales";
- Da click en el signo de "+" y espera a que cargue el repositorio (si el repositorio no carga, tal vez valga la pena refrescar la página);
- ¡Listo!

### Nota general:
Si te atoras en alguno de los pasos, seguro Google tendrá la respuesta.
