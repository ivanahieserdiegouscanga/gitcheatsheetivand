# gitcheatsheetivand
here you can see the summary
If structure
if (condición) {
		sentencias_si_verdadero;
	} else {
		sentencias_si_falso;
	}

Primary Constants Numeric Constants, Integer Constants, Real Constants, Character Constants, Single Character Constants, String Constants, Backslash Character Constants

A pointer is a variable that contains the address of a data memory or another variable that contains data in an array. This means that the pointer points to the physical space in which the data or variable is located. A pointer can point to an object of any type, for example, a structure or function. Pointers can be used to reference and manipulate data structures, to refer to dynamically allocated memory blocks and to provide arguments by reference in function calls. Many of the standard C functions work with pointers, such as scanf or strcpy. These functions receive or return a value that is a pointer. For example: Scanf passes the address of the data memory to read

Arithmetical operation:There are many assignment operators in C, which will actually be a simplification of more complex expressions, such as independent operations (+ =, - =, * =, / =, & =, ...) and before / after increasing / decreasing (++, -).
Arithmetic operators
It should be noted that the entire division and the real division differ, according to the operands.

DdF C Description
+ + Sum, addition
- - Subtraction, subtraction
. * Multiplication, product
Div / Integer division quotient
Mod% Rest entire division
//DivisionIn general, these expressions cannot be used in flowcharts.

Relational Operators
DdF C Description
>> Senior
≥> = Greater than or equal
<<Minor
≤ <= Less than or equal
= == Equal
≠! = Different
Logical operators
The operands are considered false (value 0) or certain (value other than 0). The result is always 0 or 1.
DdF C Description
^ && And, and, conjunction
∨ || Or, or, disjunction
¬! Not, no, denial	

what about git?
Git usa datos como un conjunto de copias instantáneas de un sistema de archivos miniatura
Cada vez que realizas confirmas y actualizas un cambio, o guardas el estado de tu proyecto en Git
él básicamente toma una foto del aspecto de todos tus archivos en ese momento y guarda una referencia a esa copia instantánea.
Para ser eficiente, si los archivos no se han modificado Git no almacena el archivo de nuevo
sino un enlace al archivo anterior idéntico que ya tiene almacenado.
la caracteristica mas resaltante de git es que almacena datos atravez del tiempo 

Configurar Nombre que salen en los commits:git config --global user.name "dasdo"
Configurar Email:git config --global user.email dasdo1@gmail.com
Marco de colores para los comando:git config --global color.ui true
Iniciamos GIT en la carpeta donde esta el proyecto:git init
Clonamos el repositorio de github o bitbucket:git clone <url>
Añadimos todos los archivos para el commit:git add .
Hacemos el primer commit:git commit -m "Texto que identifique por que se hizo el commit"
subimos al repositorio:git push origin master
Añadimos todos los archivos para el commit:git add .
Añadimos el archivo para el commit:git add <archivo>
Añadimos todos los archivos para el commit omitiendo los nuevos:git add --all 
Añadimos todos los archivos con la extensión especificada:git add *.txt
Añadimos todos los archivos dentro de un directorio y de una extensión especifica:git add docs/*.txt
Añadimos todos los archivos dentro de un directorios:git add docs/: GIT COMMIT
Cargar en el HEAD los cambios realizados:git commit -m "Texto que identifique por que se hizo el commit"
Agregar y Cargar en el HEAD los cambios realizados:git commit -a -m "Texto que identifique por que se hizo el commit"
De haber conflictos los muestra:git commit -a 
Agregar al ultimo commit, este no se muestra como un nuevo commit en los logs. Se puede especificar un nuevo mensaje:git commit --amend -m "Texto que identifique por que se hizo el commit"
Subimos al repositorio:git push <origien> <branch>
Subimos un tag:git push --tags+
Lista un estado actual del repositorio con lista de archivos modificados o agregados:git status
Quita del HEAD un archivo y le pone el estado de no trabajado:git checkout -- <file>
Crea un branch en base a uno online:git checkout -b newlocalbranchname origin/branch-name
Busca los cambios nuevos y actualiza el repositorio:git pull origin <nameBranch>
Cambiar de branch:git checkout <nameBranch/tagname>

