# Part#2: TypeScript Practical Exercises (Time-Boxed 20 Minutes)

1. Exercise: Scoping

Please explain what the outputs of the console logs are:

```
const logUser = function() {
    console.log(user);
    let user;
    if (!user) {
        var user = 'new User';
        console.log(user);
        user = 'deleted user';
    }
    user = 'existing user';
    console.log(user);
}
```

Answer here:

```
1:
2:
3:

```

2. Exercise: Async/Await

Develop a TypeScript function that simulates fetching data asynchronously from an API using async/await. Make an HTTP request using Axios and return the result as a resolved promise. Handle errors gracefully using try/catch.

Answer here:

```
import axios from "axios";

const fetchData = () => {

}

```

3. Exercise: Inheritance

Utilize the base class "Vehicle" and establish subclasses "Car" and "Motorcycle" that inherit from the base class. Create specific implementations for their unique behaviors.

Answer here:

```
type Vehicle = {
  name: string;
  brand: string;
  age: number;
  fuelType: boolean;
};


```

4. Exercise: Enums

Design a TypeScript enum named "MonthsOfTheYear" that represents the months of the year (e.g., January, February). Implement a function that takes a month as input and returns the following month (cyclically, December follows January).

Answer here:

```

```

5. Exercise: Type assertion

Enhance the "maintainDevice" function to handle both the "Car" and "CoffeeMachine" types. The function should accept a parameter, which can be an instance of a "Car" or a "CoffeeMachine," and assert the type to call the appropriate method "refuelTank" or "fillUpWater."

```
type Device = {
  brand: string;
  model: string;
  age: number;
}

type Car extends Device = {
  fuelType: string,
  refuelTank: function;
};

type CoffeeMachine extends Device = {
  beanType: string;
  fillUpWater: function;
};
```

Answer here:

```
const maintainDevice = () => {

}

```
