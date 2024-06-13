# Notas del curso. 

**parentElement** te lleva al elemento Padre del que estás seleccionando. 

```js
if( e.target.classList.contains('agregar-carrito') ) {
        console.log(e.target.parentElement.parentElement)
    }
```