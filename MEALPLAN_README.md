# Final Capstone: Chef's Compass, Meal Planning Application
## Team Juliett (Tech Elevator Cbus cohort[21], 2023): 
- D. Whitaker
- T. Schweyer
- R. Fogel
- K. Escondo
​
## Description
Our meal planning application allows users to search for recipes using a web API (Spoonacular) and, if they wish, browse recipes by diet style. Logged in users are also able to save recipes to their own library, as well as create and modify daily meal plans. 

## Technologies used
- Java
- Spring Boot
- SQL
- Vue.js
- RESTful APIs
- GitLab
- IntelliJ
- PostGreSQL
- Postman
- Visual Studio Code
- Material Design (Vuetify)

### API documentation​
```js 
List saved recipes
Path: /recipes
Request method: GET
Return: list of recipes
Status: 200 SUCCESS
Error: 400 Bad Request

Descr: View a saved recipe
Path: /recipes/{id}
Request method: GET
Return: list of recipes
Status: 200 SUCCESS
Error: 404 Not Found

Descr: Add (save) a recipe
Path: /recipes
Request method: POST
Return: recipe object
Status: 201 CREATED
Error: 400 Bad Request

Descr: List (view) meal plans
Path: /mealplans
Request method: GET
Return: list of meal plans
Status: 200 SUCCESS
Error: 400 Bad Request

Descr: View a meal plan
Path: /mealplans?date={date}
Request method: GET
Return: meal plan object
Status: 200 SUCCESS
Error: 404 Not Found

Descr: Add Recipe to Meal Plan
Path: /mealplans
Request method: POST
Return: meal plan object
Status: 201 CREATED
Error: 400 Bad Request

Descr: Remove Recipe from Meal Plan
Path: /mealplans/{mealPlanId}/meals/{mealId}/recipes/{recipeId}
Request method: DELETE
Status: 200 
Error: 400 Bad Request
```
## Screenshots​
![Home page](https://github.com/kescondo/kescondo/assets/143726973/b2737cfb-2705-451a-90b2-80cc9e7b1e09)
![Search recipes](https://github.com/kescondo/kescondo/assets/143726973/593861d6-4fcf-44e1-9ecc-58965177a0cb)
![Recipe detail](https://github.com/kescondo/kescondo/assets/143726973/32d3486c-bcd0-4d87-b651-8bf01f47b460)
![My saved recipes](https://github.com/kescondo/kescondo/assets/143726973/17b26251-a750-49bc-8915-c48a25a2c17e)
![Meal plan view](https://github.com/kescondo/kescondo/assets/143726973/77d553a3-56e1-4352-88fc-0d3cdb43b259)



