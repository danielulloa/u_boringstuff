# Automating the boring stuff with Python

Curso de [udemy](https://www.udemy.com/course/automate/learn/) dictado por el autor del libro Al Sweigart. Complementé con los ejercicios propuestos de cada capítulo.

## lists.ipynb
las variables son referencias de una lista, por lo tanto son mutables.

## diccionarios.ipynb
los diccionarios no tienen orden

## stringsmethods.ipynb
algunos metodos para visualizar mejor los strings a la hora de imprimirlos

## regularExpressions.ipynb
paso a paso en el uso de RegEx

## usingFiles.ipynb
uso de archivos de texto plano




## Lesson 22

Corriendo programas de python en windows

The shebang line tells your computer that you want to run the script using Python 3.
On Windows, you can bring up the Run dialog by pressing Win+R.
A batch file can save you a lot typing by running multiple commands.
The batch files you'll make will look like this:
    @py C:\Users\Al\MyPytonScripts\hello.py %*
    @pause
You'll need to add the MyPythonScripts folder to the PATH environment variable first.
Command-line arguments can be read in the sys.argv list. (Import the sys module first.)