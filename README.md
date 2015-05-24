# Javascript Listing Style
A Javascript listing style for Latex presentations with support for annotations

Use %% before and after annotation
```
%%@Inject%%(Electricity)
export class Heater {
  constructor(electricity) {
    this.electricity = electricity;
  }

  on() {
    console.log('Turning on the coffee heater...');
  }

  off() {
    console.log('Turning off the coffee heater...');
  }
}
```

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
