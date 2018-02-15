# Recipe Box - FreeCodeCamp challenge

Visit [https://zdflower.github.io/recipeBoxFCC/](https://zdflower.github.io/recipeBoxFCC/) (In progress) 

## Comments

At the begining I wanted to divide the page into components, generalize some for then apply that to particular cases, reuse code, etc. but failed huge because yet I didn't figure it out how to get the what I was looking for. 
In the meantime, I wrote a version where the Page component renders almost all directly and there is repeated code in some places.
You can create new recipes, delete a recipe, store them in the local storage and edit an existing recipe.
In the first version the editing was not quite ok, but finally I find out how to properly edit a recipe and make a small change in EditForm (assign the name and the ingredients of the recipe to the state of the EditForm instead of using placeholder in the form).

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
