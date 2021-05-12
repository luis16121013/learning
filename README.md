# Learning and Documenting with Markdown
### by [Luis angel Pfuño canales](https://lapcweb.ga)
>**"Estaremos aprendiendo lo siguiente"**
* **go**
* **javascript**
* **html**
* **css**
* **Reactjs**
* **Sveltejs**

## 1. Go
### 1.1 Hola mundo
##### Creando nuestro primer programa en Go
~~~
1. creamos nuestro archivo "main.go"
2. escribimos el siguiente codigo
~~~

```go
1 package main
2
3 import "fmt"
4
5 func main() {
6 	fmt.Println("hola")
7 }
8
```
**package main:** Cada archivo go debe comenzar con la declaración **"package"** aqui se utiliza el 
nombre del paquete "main".

**import "fmt":** el paquete **"fmt"** se importa y se utilizará dentro de la funcion principal para
imprimir texto en salida estándar.

**fmt.Println("hola"):** la funcion ***"Println()"*** del paquete **"fmt"** se utiliza para escribir texto
en la salida estándar.

### 1.2 Variables
##### Declaracion de variables (formas)
- Declarar una sola variable **var name type**
```go
package main

import "fmt"

func main() {
	var miVariable string
	fmt.Println(miVariable)
}

```
- Declarar variable con valor inicial **var name type = initialValue**
```go
package main

import "fmt"

func main() {
	var miVariable string = "mi nombre"
	fmt.Println(miVariable)
}

```
- Inferencia de tipo **var name = initialValue**
```go
package main

import "fmt"

func main() {
	var nombre = "mi nombre"
	var edad = 30

	fmt.Println(nombre)
	fmt.Println(edad)
}

```
- Declaracion de varias variables **var name,name2 = initialValue,initialValue2**
```go
package main

import "fmt"

func main() {
	var nombre,edad = "mi nombre",30

	fmt.Println(nombre)
	fmt.Println(edad)
}

```

```go
package main

import "fmt"

func main() {
	var codigo,edad int

	codigo = 122832
	edad = 40

	fmt.Println(codigo)
	fmt.Println(edad)
}

```

```go
package main

import "fmt"

func main() {
	var (
		nombre = "mi nombre"
		edad = 39
	)

	fmt.Println(nombre)
	fmt.Println(edad)
}

```

- Declaracion corta **name := initialValue**
```go
package main

import "fmt"

func main() {
	nombre := "mi nombre"
	fmt.Println(nombre)
}

```
