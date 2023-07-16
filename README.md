```js
class AboutMe extends Human {
  constructor() {
    this.name = "Talha Mujahid";
    this.role = "Software Engineer";
    this.interests = ["Reading", "Coding", "Blogging"];
  }

  sayHi() {
    console.log(`Hi, I'm ${this.name}. Nice to meet you!`);
  }
}

const me = new AboutMe();
me.sayHi();
```
