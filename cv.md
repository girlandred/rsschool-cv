# **Maryna Shyta**

_Software Engineer based in Kyiv_

---

## About Me

I am a young software developer with a skill for working hard to get the best results
My main achievement in my 19 years is solving quadratic equations with Vieta's theorem
Since I have been working on a real project for a year now, I have experience of working in a team
My main goal is to achieve a high level of knowledge in the field of web development
Over the past three years, I have developed in such areas as data engineering, development of the server-side of applications and the user-side
I also have knowledge in the field of deploying servers, creating docker containers

---

## Skills

### Programming languages

- **C/C++**
- **Python**
- **PHP** _(Laravel)_
- **JavaScript** _(Vue.js/React.js)_

### Deployment

- **YAML**
- **Docker**
- **AWS**
- **Azure**

### Methodology

- **Scrum**
- **Kanban**

---

## Experience

**Agiliway Junior Software engineer** _(Dec 2021 - Present)_

[CiviMobile](https://civimobile.org/ua/) is a native mobile application that allows CiviCRM users to leverage the combined benefits of the software and their smartphones.

- **_Technologies used:_** React, JavaScript, PHP.

[Whosmailingwhat](https://www.whosmailingwhat.com/)

- **_Technologies used:_** HTML, SCSS, JavaScript, PHP(Laravel).

**Pet** **Projects**

[Recipe App](https://github.com/girlandred/recipe-app) is full-stack app for creating recipes, leaving reviews, collecting achievements

- **_Technologies used:_** Tailwind, PHP(Laravel/Livewire).

[Data Engineering](https://github.com/girlandred/data-engineering) projects for data engineering and analysis

- **_Technologies used:_** Pandas, Seaborn, Plotly, Matplot.

---

## Education

**Bachelor of Computer Science** in Software Engineering studies

- [Lviv National University](https://lnu.edu.ua/) - Lviv, Ukraine _(2020 - 2024)_

**Finished** **Courses**

- [Agiliway PHP training](https://agiliway.com/career/agiliway-training-center/) - Lviv, Ukraine _(2021 - 2022)_

- [Epam Frontend School](https://careers.epam.ua/learning) - Lviv, Ukraine _(2020 - 2021)_

- [Data Science](https://www.coursera.org/account/accomplishments/certificate/TLL87BQB9CH4) - Lviv, Ukraine _(2022)_

---

## Languages

**English:** B2+

**German:** B1+

**Ukrainian:** Native

---

## Code Example

```js

class Person {
  constructor(name, surname, birthYear) {
    this.name = name;
    this.surname = surname;
    this.birthYear = birthYear;
  }

  get fullName() {
    return `${this.name} ${this.surname}`;
  }

  set fullName(value) {
    [this.name, this.surname] = value.split(" ");
  }

  age() {
    let date = new Date();
    return date.getFullYear() - this.birthYear;
  }

  introducing() {
    alert("My name is " + this.fullName);
    alert("I am " + this.age() + " years old.");
  }
}

class Programmer extends Person {
  constructor(name, surname, birthYear, profession, stack) {
    super(name, surname, birthYear);
    this.profession = profession;
    this.stack = stack;
  }
}
let person = new Programmer("Maryna", "Shyta", 2003, 'Backend Developer', 'PHP');
person.introducing();
person.profession;
```

---

[Email](mailto:maryna.shyta@gmail.com) / [LinkedIn](https://www.linkedin.com/in/marynashyta/) / [GitHub](https://github.com/girlandred)
