# Ejercicio de Sincronización

## Los alumnos y el asesor

### Planteamiento
Un profesor de la facultad asesora a varios estudiantes, y estamos
en su horario de atención.



### Reglas 
* Un profesor tiene *__x__* sillas en su cubículo
    * Cuando no hay alumnos que atender, las sillas sirven como
sofá, y el profesor se acuesta a dormir la siesta.

* Los alumnos pueden tocar a su puerta en cualquier momento,
pero no pueden entrar más de *__x__* alumnos

* Para evitar confundir al profesor, sólo un alumno puede
presentar su duda (y esperar a su respuesta) al mismo tiempo.
    * Los demás alumnos sentados deben esperar pacientemente su
turno.
    * Cada alumno puede preguntar desde 1 y hasta *__y__* preguntas
(permitiendo que los demás alumnos pregunten entre una y
otra)


## Lenguaje y entorno

Para resolver el problema usamos python, con las siguientes librerias:
* threading: Para crear procesos paralelos
* time: Para poder coordinarlos
* random: Para crear caos y entre estos y que el programa tenga algo que resolver 

### Requisitos
* Python 3 instalado
* Cualquier sistema operativo 

### Cómo ejecutar el programa

1. Abrir una terminal.
2. Navegar a la carpeta donde se encuentra el archivo `asesor.py`.

```bash
cd ruta/de/la/carpeta
```
3. Ejecutar programa:

```bash
python3 asesor.py
```



## Estrategia de sincronización

Usamos mutext



## Usamos refinamiento?

no lo se 



## duda o meditaciones 

blah blah 



## Autores

Chacon Hugo
Valdez Sebastian

Materia: **Sistemas Operativos**
Semestre: **2026-2**