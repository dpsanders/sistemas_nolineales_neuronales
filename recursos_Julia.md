# Recursos para Julia

- Sitio web principal para todo lo que es Julia: http://www.julialang.org

- Usar Julia en línea, sin instalar nada:
    - JuliaBox: http://next.juliabox.com
    - CoCalc:  http://cocalc.com (incluye modo colaborativo)

- Aprender Julia:
    - Lista de recursos: http://www.julialang.org/learning
    - Cheatsheets (primeros dos en la sección de Recursos)
    - Notebooks de tutorial disponibles adentro de JuliaBox o [aquí](https://github.com/xorJane/Introduction_to_Julia_tutorials)


- Entornos integrados para desarrollar código de Julia:
    (Software libre, disponible en cualquier plataforma):
    - [Juno IDE](http://junolab.org/)
    - [Visual Studio Code Julia plugin](https://marketplace.visualstudio.com/items?itemName=julialang.language-julia) 

## Instalación local de Julia

Para instalar Julia localmente:    
- Baja e instala la versión estable de Julia (0.6.2) desde http://www.julialang.org/downloads
- Corre Julia

- Si usas Linux:
```
julia> ENV["JUPYTER"] = ""
```

- Ahora instala el paquete de IJulia:
```
julia> Pkg.add("IJulia")
```

- Abre el notebook:
```
julia> using IJulia
julia> notebook()
```
