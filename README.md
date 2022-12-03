# FRIGO

# ROUTES

Relevant endpoints SERVER

| Route                                               | HTTP Verb  | Description                     |
| --------------------------------------------------- | ---------- | ------------------------------- |
| `/api/auth/signup`                                  | POST       | SIGNUP                          |
| `/api/auth/login`                                   | POST       | LOGIN                           |
| `/api/auth/verify`                                  | GET        | VERIFY TOKEN                    |
| `/api/recipes/create`                               | POST       | CREATE RECIPE IN DATABASE       |
| `/api/recipes/edit`                                 | POST       | UPDATE RECIPE IN DATABASE       |
| `/api/recipes/:id/information`                      | GET        | GET ONE RECIPE FROM DATABASE    |
| `/api/recipes/complexSearch?query=query`            | GET        | GET RECIPE BY CATEGORY          |
| `/api/recipes/findByIngredients?ingredients=query`  | GET        | GET RECIPE BY INGREDIENT        |


<!-- PREGUNTAR SI ES NECESARIO QUE NUESTRAS RUTAS SEAN IGUALES A LAS DE LA LLAMADA A LA API -->


Relevant endpoints CLIENT

| Route                          | Description                                             | Protected   |
| ------------------------------ | ------------------------------------------------------- |-------------|
| `/signup`                      | SIGNUP                                                  | X           |
| `/login`                       | LOGIN                                                   | X           |
| `/home`                        | HOME PAGE, SEARCH BY INGREDIENTS AND SEE CATEGORIES     | X           |
| `/recipe/:id`                  | DETAILS OF CHOOSED RECIPE                               | X           |
| `/recipe/:id/edit`             | EDIT RECIPE                                             | ✔           |
| `/about`                       | ABOUT US PAGE                                           | X           |
| `/profile/:id`                 | USER PROFILE                                            | ✔           |
| `/profile/:id/edit`            | EDIT USER PROFILE                                       | ✔           |
| `/shopping-list`               | YOUR SHOPPING LIST                                      | ✔           |
| `/*`                           | 404                                                     | X           |


<!-- | `/my-recipes`                  | POST       | INDEX PAGE          | ✔           |
| `/fav-recipes`                 | POST       | INDEX PAGE          | ✔           | -->