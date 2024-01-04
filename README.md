# Hello there 👋

![visitors](https://visitor-badge.laobi.icu/badge?page_id=gusram01.gusram01)


```typescript
class Me {
  readonly #name: string;
  readonly #spokenLanguages: string[] = [];
  #role: string;

  constructor(
    name: string,
    role: string,
    spokenLanguages = ['es', 'en']
  ){
    this.#name = name;
    this.#spokenLanguages = this.#spokenLanguages
      .splice(this.#spokenLanguages.length, 0, ...spokenLanguages);
  }

  sayHi(): void {
    console.log('Thanks for dropping by, hope you find some of my work interesting :nerd_face: :thought_balloon:')
  }
}

const Gus = new Me('Gus Ramírez', 'Frontend Engineer');

Gus.sayHi();
```

## Technologies

**Programming Languages**

![Typescript](https://img.shields.io/badge/Code-Typescript-informational?style=flat&logo=typescript&logoColor=white)

![Go](https://img.shields.io/badge/Code-Go-informational?style=flat&logo=go&logoColor=white)

![Javascript](https://img.shields.io/badge/Code-Javascript-informational?style=flat&logo=javascript&logoColor=white)

**Frontend Frameworks**

![Angular](https://img.shields.io/badge/Code-Angular-informational?style=flat&logo=angular&logoColor=white)

![Vue](https://img.shields.io/badge/Code-Vue-informational?style=flat&logo=vue&logoColor=white)

![React](https://img.shields.io/badge/Code-React-informational?style=flat&logo=react&logoColor=white)

![Svelte](https://img.shields.io/badge/Code-Svelte-informational?style=flat&logo=svelte&logoColor=white)

**Backend Frameworks**

![Express](https://img.shields.io/badge/Code-Express-informational?style=flat&logo=express&logoColor=white)

![Fiber](https://img.shields.io/badge/Code-Fiber-informational?style=flat&logo=fiber&logoColor=white)



