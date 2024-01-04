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

> ![Typescript](https://img.shields.io/badge/Code-Typescript-informational?style=flat&logo=typescript)

