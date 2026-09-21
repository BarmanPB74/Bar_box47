# Bar_box47 · archivo histórico

El proyecto **BAR BOX** vive ahora en un solo repositorio:

### → https://github.com/BarmanPB74/Bar_box

Aquí quedó el primer intento en Python puro (`historia/bar_box_primer_intento.py`):
un inventario por consola con un bucle `while` y un diccionario. No se borra —
es de donde salió todo — pero ya no se desarrolla.

## Por qué se unificó

Tres repositorios con el mismo proyecto obligan a decidir en cuál está lo bueno
cada vez que te sientas a trabajar, y a Claude a leer los tres para entender el
estado. Un repositorio, una rama de trabajo, una fuente de verdad.

## Qué hacer desde el teléfono

```bash
cd ~
git clone https://github.com/BarmanPB74/Bar_box.git bar-box
cd bar-box && git checkout claude/bar-box-bitacora-mesas-k1s9nj
bash scripts/bb.sh
```

La guía completa de Termux está en `docs/TERMUX_F8.md` del repositorio principal.
