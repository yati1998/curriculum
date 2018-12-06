1. Make a new project directory containing js file and an html file.  We are going to leave css out of this project.
1. create an array of at least 2 objects in your js file.  Each object should have a few keys and values for a restaurant's info:
```
const restaurantList = [
  {
    name: "Flour and Water",
    type: "Italian",
    popularDish: "pizza",
    neighborhood: "The Mission"
    pricePoint: "high-priced",
    summary: "Flour and Water is a high-priced Italian restaurant in The Mission.  They are known for their pizza."
  },
  {
    name: "San Jalisco",
    type: "Mexican",
    popularDish: "chicken mole",
    neighborhood: "The Mission",
    pricePoint: "moderately-priced",
    summary: "San Jalisco is a moderately-priced Mexican   restaurant in The Mission.  They are known for their chicken mole."
  }
];
```
1. Next in your js file, create a class called 'Restaurant' with a constructor that accepts all of the keys in your restaurant objects.
```
class Restaurant {
  constructor(name, type, popularDish, neighborhood, pricePoint) {
    this.name = name;
    this.type = type;
    this.popularDish = popularDish;
    this.neighborhood = neighborhood;
    this.pricePoint = pricePoint;
  }
}
```
1. Create a class method called summary(). This method should use the object's properties to create a string that summarizes all of the restaurant's info.
```
class Restaurant {
  constructor(name, type, popularDish, neighborhood, pricePoint) {
    this.name = name;
    this.type = type;
    this.popularDish = popularDish;
    this.neighborhood = neighborhood;
    this.pricePoint = pricePoint;
  }
  summary() {
    return (this.name + " is a " + this.pricePoint + " restaurant in " + this.neighborhood + ". They are known for their " + this.popularDish);
  }
}
```
