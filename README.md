# Cómo Utilizar Markdown en GitHub

Este archivo README.md tiene como objetivo explicar cómo utilizar Markdown en GitHub, especialmente en los archivos `README`.

## ¿Qué es Markdown?

Markdown es un lenguaje de marcado ligero que puedes usar para darle formato al texto en GitHub. Puedes utilizarlo para crear listas, enlaces, imágenes, tablas y más, sin necesidad de usar un editor WYSIWYG (What You See Is What You Get).

## Estructura Básica de un Archivo README

Un archivo `README.md` es comúnmente el primer archivo que los usuarios ven cuando visitan un repositorio. Sirve para explicar el propósito del proyecto, cómo configurarlo y cómo usarlo.

### 1. Títulos

Usa el símbolo de almohadilla `#` para crear títulos. Cuantas más almohadillas, menor será el nivel del título.

```markdown
# Título Principal
## Título Secundario
### Título Terciario
```
### 2. Negrita y Cursiva
Para poner texto en negrita usa dos asteriscos ** o dos guiones bajos __:
```markdown
**Texto en negrita**
```
Para poner texto en cursiva, usa un asterisco * o un guion bajo _:
```markdown
*Texto en cursiva*
```


### 3. Listas
Puedes crear listas con viñetas usando -, + o *, y listas numeradas usando números seguidos de un punto.
#### Listas con viñetas:
``` 
- Elemento 1
- Elemento 2
- Elemento 3 
```
#### Listas enumerdadas:
```
1. Primer ítem
2. Segundo ítem
3. Tercer ítem
```
### 4. Enlaces
Puedes crear enlaces con el siguiente formato:
```
[Texto del enlace](URL)
```
Ejemplo:
```
[GitHub](https://github.com/)
```
### 5. Imágenes
Las imágenes se insertan de manera similar a los enlaces, pero añades un ! al principio.
```
![Texto alternativo](URL-de-la-imagen)
```
Ejemplo del código:
```
![Logo de MarkDown](https://i.blogs.es/eaff13/markdown-que-es-1/1366_2000.jpg)
```
Resultado:
![Logo de MarkDown](https://i.blogs.es/eaff13/markdown-que-es-1/1366_2000.jpg)
## 6. Bloques de Código

Para mostrar fragmentos de código usa tres tildes invertidas ``` (backticks). Si es un solo bloque de código:
```markdown
Código aquí
```
Si quieres resaltar el lenguaje de programación (como C++) puedes especificarlo:

Por ejempo:
```cpp
//C++ 
#include <iostream>
using namespace std;

int main() {
    cout << "Hello World" << endl;
    return 0;
}
```
```py
//Python
print("Hello World")
```
```javascript
//JavaScript
console.log("Hello World");
```
```html
<!--HTML-->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hello World</title>
</head>
<body>
    <h1>Hello World</h1>
</body>
</html>
```
```css
/*CSS*/
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
}
h1 {
    color: blue;
    text-align: center;
}
```
```java
//Java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}
```
```bash
#Bash
echo "Hello World"

```
```ruby
#Ruby
puts "Hello World"
```
```php
//PHP
<?php
echo "Hello World";
?>
```
```swift
//Swift
print("Hello World")
```
```sql
--SQL
SELECT 'Hello World';
```

Ejemplo:
```cpp
#include <iostream>
using namespace std;

int main() {
    cout << "¡Hola, mundo!" << endl;
    return 0;
}
```
### 7. Tablas
Las tablas en Markdown se crean utilizando guiones `-` para las filas de encabezado y tuberías `|` para las columnas.
```markdown
| Columna 1 | Columna 2 | Columna 3 |
|-----------|-----------|-----------|
| Fila 1    | Fila 1    | Fila 1    |
| Fila 2    | Fila 2    | Fila 2    |

```
### 8. Citas
Para crear citas, usa el símbolo > al principio de la línea.
```
> Esto es una cita.
```
### 9. Enlaces a Archivos
Puedes enlazar archivos dentro de tu repositorio utilizando la sintaxis de enlace normal, pero apuntando a la ruta relativa del archivo.
```
[Ver archivo](ruta/del/archivo.ext)
```
### 10. Uso de Emojis
GitHub también admite emojis, que puedes agregar utilizando un código entre dos puntos :, como por ejemplo:
```
:smile: :rocket: :star:
```
Resultado:
😊 🚀 ⭐

##### ¿Por qué usar Markdown en GitHub?
##### Facilidad de uso:
Markdown es sencillo de aprender y de usar.
###### Formateo rápido:
Te permite agregar formato sin tener que lidiar con un editor visual.
######  Compatibilidad: 
GitHub renderiza archivos Markdown automáticamente, lo que te permite presentar tu proyecto de manera atractiva.
###### ¡Eso es todo! 

