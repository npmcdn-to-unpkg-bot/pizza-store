# Pizza-store App
Using React to fetch data from JSON API and populate the data on single page
JSON data is pulled from http://localhost:8080/pizza that look like this:
```
[{
  "id": "d0765cc5-2085-4867-91f0-2e83365e6d95",
  "name": "Hawaiian Super Supreme",
  "price": 9.5,
  "toppings": [{
    "id": "90ae7eac-1e4a-408b-8551-d7ae4c12e9bb",
    "name": "Quesadilla"
  }, {
    "id": "0218df7e-1eda-4909-a83f-5187b35ca079",
    "name": "Fried clams"
  }]
}]
```

## The hierarchy of the components:
- Navbar
- Header
- Pizza
  * FindPizza
  * PizzaList
    * Show Toppings