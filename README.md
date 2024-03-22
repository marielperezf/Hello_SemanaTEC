#  CAMBIO PARA EL VIDEO
# - Hello_SemanaTEC
# - Mariel Gisela Perez Ferrusquia :white_heart:
# ITC
# Monterrey
## Rayados
## **Semana TEC**

# 2. Tipos de Letra
**Bold**
*Italic*
> Hola

> AdioS

# 3. Lista Enumerada
1. Gorditas Doña Tota, Cd. Victoria
2. Corundas de Morelia
3. Tortas de la Barda, Tampico
4. La Parroquia, Veracruz
5. Tacos Alfaro, Centrito Valle
6. Tacos de Villda de Santiago, Garza Sada
7. Tacos Atarantados, Vasconcelos
8. Chilaquiles TEC

# 4. Lista con Viñetas
1. Tacos Guero
2. Tacos la Morelense
3. Tacos el Porton

# 5.Codigo
```python
from turtle import *
from freegames import vector

def line(start, end):
    """Draw line from start to end."""
    up()
    goto(start.x, start.y)
    down()
    goto(end.x, end.y)

def square(start, end):
    """Draw square from start to end."""
    up()
    goto(start.x, start.y)
    down()
    begin_fill()

    for count in range(4):
        forward(end.x - start.x)
        left(90)

    end_fill()

def circle(start, end):
    """Draw circle from start to end."""
    pass  # TODO

def rectangle(start, end):
    """Draw rectangle from start to end."""
    pass  # TODO

def triangle(start, end):
    """Draw triangle from start to end."""
    pass  # TODO

def tap(x, y):
    """Store starting point or draw shape."""
    start = state['start']

    if start is None:
        state['start'] = vector(x, y)
    else:
        shape = state['shape']
        end = vector(x, y)
        shape(start, end)
        state['start'] = None
```

# 6. Regla 
---

# 7. Link
-	[freegames](https://grantjenks.com/docs/freegames/)
-	[Markdown](https://www.markdownguide.org/cheat-sheet/)

# 8. Imagenes
![Monterrey](https://upload.wikimedia.org/wikipedia/commons/thumb/f/f7/Monterrey_pano_campestre_%2818135627388%29.jpg/1920px-Monterrey_pano_campestre_%2818135627388%29.jpg)

# 9. Tabla
| Syntax | Description |
| ----------- | ----------- |
| TC1028 - PERIODO 2 | PYTHON |
| TC1028 - PERIODO 2 | PYTHON |
| TC1028 - PERIODO 2 | PANDAS |

# 10. Lista de Equipo
- [x] Mariel Perez
- [X] Martha Mendoza
- [X] Valeria Lopez

:grinning::grinning::grinning:
