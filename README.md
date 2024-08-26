# Arquitectura empresarial

Este projecto es una prueba para mejorar nuestra habilidades Ing de Sistemas

## Prerequisitos
No es necesario instalar nada para modificar pero siquieres ir viendo como queda puedes sigue los pasos de :
[Cómo escribir LaTeX en VS Code | Tutoriales G&O ](https://www.youtube.com/watch?v=e3LxLIRQf-c)

tambien puede usar [overleaf](https://www.overleaf.com) para abrir el proyecto pero las modificaciones deben estar en este archivo.

Recuerda siempre construir el pdf en una carpeta /build 

## Ayudas

### Agregar una imagen

agrega la figura en la carpeta en figura con un nombre entendible y luego llamalo con este pedzo de codigo, dale una descripcion

```[latex]
\begin{figure}[!ht]
    \centering
    \includegraphics[width=0.8\textwidth]{producto_insuma_app.png}
    \caption{App insuma para la logistica entre clientes}
\end{figure}
```

### Enumerar

```[latex]
\begin{itemize}
    \item {Amaut Guzmán, Marcelo Fabian }
    \item {Baldeon Peña, Juancarlos }
    \item {Hernandez Ormeño, Roberth Alessandre }
    \item {Livise Larico, Rafael Enrique }
\end{itemize}
```