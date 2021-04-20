# CoppeliaSim_FlisolBA

<p align="center">
 <img width="100px" src="https://github.com/cabustillo13/CoppeliaSim_FlisolBA/blob/main/Recursos/robot.svg" align="center" alt="FLISoL BA" />
 <h2 align="center">FLISoL BA 2021</h2>
 <p align="center"><b>Material de la charla "Robótica Low Cost con Python" presentada en el FLISol BA 2021.</b></p>

</p>
  <p align="center">
    <a href="https://github.com/cabustillo13/CoppeliaSim_FlisolBA/actions/new">
      <img alt="Tests Passing" src="https://github.com/anuraghazra/github-readme-stats/workflows/Test/badge.svg" />
    </a>
        <a href="https://github.com/cabustillo13/CoppeliaSim_FlisolBA/issues">
      <img alt="Issues" src="https://img.shields.io/github/issues/cabustillo13/CoppeliaSim_FlisolBA?color=0088ff" />
    </a>
    <a href="https://github.com/cabustillo13/CoppeliaSim_FlisolBA/pulls">
      <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/cabustillo13/CoppeliaSim_FlisolBA?color=0088ff" />
    </a>
    <br />
</p>

## FLISoL
Es el evento de difusión de Software Libre más grande en Latinoamérica y está dirigido a todo tipo de público: estudiantes, académicos, empresarios, trabajadores, funcionarios públicos, entusiastas y aún personas que no poseen mucho conocimiento informático. 
![Link al evento](https://eventol.flisol.org.ar/events/flisol-ba/)

## Descripción de la charla
Probar, testear, romper, modificar y crear grandes proyectos de robótica con Coppelia Sim + Jupyter Notebook con **PYTHON**.

Los apuntes se encuentran acá: ![PDF](https://github.com/cabustillo13/CoppeliaSim_FlisolBA/blob/main/Recursos/FLISol_BA_2021.pdf) | ![Diapositivas](https://github.com/cabustillo13/CoppeliaSim_FlisolBA/blob/main/Recursos/FLISol_BA_2021.odp) .

## Configuración API 
Recorda colocar los siguientes archivos junto a tus escenarios de Coppelia Sim: *sim.py*, *simConst.py* y *remoteApi.so*. 
<br>Deben posicionarse en la carpeta donde descargaste Coppelia Sim y buscar los archivos en los siguientes paths o routes.

- **sim.py** y **simConst.py** (depende del lenguaje de programación a usar) se encuentra en: 
```
./programming/remoteApiBindings/python/python/
```

- **remoteApi.so** (depende del sistema operativo) se encuentra en: 
```
./programming/remoteApiBindings/lib/lib/
```

En mi caso se utilizó el lenguaje de programación Python en el sistema operativo Kubuntu 18_04.

## Licencia
Este proyecto tiene licencia MIT.
