# recipeApp
Ionic app that organizes a collection of recipes into a set of cards that is viewed one card at a time.
Note: datasource has the following JSon structure:

[{
  recipeId: 0, 
  recipeCards: [{
    cardId:0,
    cardTitle: "Recipe Name",
    cardDetail: "Recipe Description",
    cardImage: "Feature Image URL",
  }, {
    cardId: 1, 
    cardTitle: "Ingredients",
    ingredients: [
      "ingredient 1",
      "ingredient ...",
      "ingredient N"
    ]
  }, {
    cardId: 2,
    cardTitle: "Step 1",
    cardImage: "Image URL",
    cardDetail: "Step 1 Details"
  }]
}]

