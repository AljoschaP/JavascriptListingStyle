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

![Example](https://github.com/AljoschaP/JavascriptListingStyle/blob/master/listingstyle.png)
