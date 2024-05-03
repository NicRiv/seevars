# seevars

Muestra las variables que en el prompt se declararon.

## Instalación
```
    pip install seevars
```

## Implementación
Abrir REPL de Python y luego:
```python
from seevars import show
```

Para ver las variables declaradas en el prompt:
```python
show.shows(vars())
show.value(vars())
```
<small><i>Importante agregar 'vars()' como argumento.</i></small>

## Pythonstartup

<b><i>Optimiza tu flujo de trabajo en el REPL cargando el módulo una sola vez.</i></b>
```bash
echo "from seevars import show" >> ~/.pythonstartup
```

luego, agrega el archivo a la variabe de entorno y ésta en `~/.bashrc`
```bash
export PYTHONSTARTUP=$HOME/.pythonstartup
```
