# Recipe Box - FreeCodeCamp challenge

Visit [https://zdflower.github.io/recipeBoxFCC/](https://zdflower.github.io/recipeBoxFCC/) (In progress) 

## Comentarios

En un primer momento quise separar en componentes, generalizar algunos para luego aplicar a casos particulares, reutilizando código, pero fallé estrepitosamente pues aún no desentrañé cómo hacer para lograr el funcionamiento deseado.
Mientras tanto, escribí una versión donde el componente Page renderea casi todo directamente y hay bastante redundancia.
Se pueden crear nuevas recetas, se pueden borrar, se guardan en el localStorage, se puede editar una receta existente.
Sobre la función de editar: me gustaría mejorarla, que realmente pudiera editarse en el sentido de poder reutilizar el contenido existente y no reemplazarlo completamente por otro, como cuando se edita un texto en un procesador y no se tiene que volver a escribir de cero.

## User stories

[https://www.freecodecamp.org/challenges/build-a-recipe-box](https://www.freecodecamp.org/challenges/build-a-recipe-box)

- [x] I can create recipes that have names and ingredients.
- [x] I can see an index view where the names of all the recipes are visible.
- [x] I can click into any of those recipes to view it.
- [x] I can edit these recipes.
- [x] I can delete these recipes.
- [x] All new recipes I add are saved in my browser's local storage. If I refresh the page, these recipes will still be there.

## Readings

* [Web Storage API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Storage_API)
* HTML5 - [Storage](https://www.html5rocks.com/en/features/storage)
* [Store data in web browsers storage](https://forum.freecodecamp.org/t/store-data-in-web-browsers-storage/16154)
* [How do I store an array in localStorage](https://stackoverflow.com/questions/3357553/how-do-i-store-an-array-in-localstorage)
* [Forms](https://reactjs.org/docs/forms.html)
* [How to code a form in React](https://www.youtube.com/watch?v=qH4pJISKeoI)
* [Problems with setState handlers in react](https://stackoverflow.com/questions/44438117/problems-with-setstate-handlers-in-react)
* [Sass Shop](http://www.sassshop.com/)
