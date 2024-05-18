# libft

<h1 align=center>Libft. Tu primera librería</h1>

La realización del proyecto Libft ha sido una experiencia enriquecedora que me ha proporcionado habilidades fundamentales en programación en C. A lo largo de este proyecto, me sumergí en el desarrollo de mi propia biblioteca personalizada, implementando funciones esenciales de la biblioteca estándar de C (Libc).

Al abordar aspectos clave como la manipulación de cadenas, la gestión de memoria, la entrada/salida de archivos y operaciones matemáticas, gané un profundo entendimiento de cómo funcionan estas funciones básicas a un nivel más interno. Crear mi propia implementación de estas funciones no solo fue un desafío técnico significativo, sino que también me brindó la oportunidad de aplicar y consolidar mis conocimientos en programación en C.

La evolución constante de la Libft a lo largo del currículo de 42 me permitió enriquecerla progresivamente, asegurándome siempre de cumplir con las restricciones específicas de funciones permitidas en cada proyecto subsiguiente. Esta biblioteca personalizada ahora sirve como una sólida base para futuros proyectos, demostrando las habilidades y competencias que he adquirido a lo largo de mi trayectoria en 42.

## Tabla de contenidos

- [¿Qué es `Libft`?](#qué-es-libft)
- [¿En qué consiste?](#en-qué-consiste)
- [¿Qué es `Makefile` (y como hacerlo)?](#qué-es-makefile-y-cómo-hacerlo)
- [Listado de funciones](#lista-de-funciones)

 <hr>

### ¿Qué es `Libft`?


La Libft es un proyecto fundamental en el contexto del currículo de 42, diseñado para proporcionar a los estudiantes una comprensión profunda de las funciones básicas de la biblioteca estándar de C (Libc). En este proyecto, los participantes tienen la tarea de implementar sus propias versiones de funciones estándar de C, abordando aspectos esenciales como manipulación de cadenas, gestión de memoria, entrada/salida de archivos y operaciones matemáticas.

### ¿En qué consiste?

1. Instrucciones generales
2. Parte obligatoria
   <br>
   2.1. Consideraciones técnicas
   <br>
   2.2. Funciones de `libc`: algunas de las funciones estándar de C para manipular memoria y strings.
   <br>
   2.3. Funciones adicionales: funciones que, o no son de la librería `libc`, o lo son pero de una forma distinta, que pueden útiles para proyectos posteriores.
3. Parte bonus
   <br>
   Funciones interesantes para la manipulación de listas.

### ¿Qué es [Makefile](./Makefile) (y cómo hacerlo)?

Un fichero `Makefile` es un archivo de texto que describe las instrucciones que debe ejecutar el comando `make`, que lee el archivo y realiza las tareas necesarias para compilar y construir el programa de forma automatizada.
El manual de la GNU recomienda escribirlo con mayúscula porque suele aparecer cerca de otros archivos descriptivos como README, y ha de ser personalizado para adaptarse a las necesidades del proyecto, permitiendo que el desarrollador controle la compilación y construcción de software. También permite la compilación parcial de archivos, de modo que sólo se compilan los archivos que han cambiado desde la última compilación, lo que acelera el proceso de construcción y ahorra tiempo de desarrollo. Esta [playlist de YouTube](https://www.youtube.com/playlist?list=PLTd5ehIj0goOrqKZPvq1Np-8PUFcQSSm-) explica los primeros pasos para crear un Makefile.

## Lista de funciones

|     Funciones de libc     |      Funciones adicionales      |   Parte bonus   |
| :-----------------------: | :-----------------------------: | :-------------: |
| [ft_isalpha](ft_isalpha.c) |     [ft_substr](ft_substr.c)     |    [ft_lstnew](ft_lstnew_bonus.c)     |
| [ft_isdigit](ft_isdigit.c) |    [ft_strjoin](ft_strjoin.c)    | [ft_lstadd_front](ft_lstadd_front_bonus.c) |
| [ft_isalnum](ft_isalnum.c) |    [ft_strtrim](ft_strtrim.c)    |   [ft_lstsize](ft_lstsize_bonus.c)    |
| [ft_isascii](ft_isascii.c) |      [ft_split](ft_split.c)      |   [ft_lstlast](ft_lstlast_bonus.c)   |
| [ft_isprint](ft_isprint.c) |       [ft_itoa](ft_itoa.c)       | [ft_lstadd_back](ft_lstadd_back_bonus.c)  |
|  [ft_strlen](ft_strlen.c)  |    [ft_strmapi](ft_strmapi.c)    |  [ft_lstdelone](ft_lstdelone_bonus.c)   |
|  [ft_memset](ft_memset)  |   [ft_striteri](ft_striteri.c)   |   [ft_lstclear](ft_lstclear_bonus.c)   |
|   [ft_bzero](ft_bzero.c)   | [ft_putchar_fd](ft_putchar_fd.c) |   [ft_lstiter](ft_lstiter_bonus.c)    |
|  [ft_memcpy](ft_memcpy.c)  |  [ft_putstr_fd](ft_putstr_fd.c)  |    [ft_lstmap](ft_lstmap_bonus.c)    |
| [ft_memmove](ft_memmove.c) | [ft_putendl_fd](ft_putendl_fd.c) |                 |
| [ft_strlcpy](ft_strlcpy.c) |  [ft_putnbr_fd](ft_putnbr_fd.c)  |                 |
| [ft_strlcat](ft_strlcat.c) |                                 |                 |
| [ft_toupper](ft_toupper.c) |                                 |                 |
| [ft_tolower](ft_tolower.c) |                                 |                 |
|  [ft_strchr](ft_strchr.c)  |                                 |                 |
| [ft_strrchr](ft_strrchr.c) |                                 |                 |
| [ft_strncmp](ft_strncmp.c) |                                 |                 |
|  [ft_memchr](ft_memchr.c)  |                                 |                 |
|  [ft_memcmp](ft_memcmp.c)  |                                 |                 |
| [ft_strnstr](ft_strnstr.c) |                                 |                 |
|    [ft_atoi](ft_atoi.c)    |                                 |                 |
|  [ft_calloc](ft_calloc.c)  |                                 |                 |
|  [ft_strdup](ft_strdup.c)  |                                 |                 |
