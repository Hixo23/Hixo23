```ts
type Contact = {
    discord: string
}

class Hixo {
    private hobbies : string[] = [];
    private technologies : string[] = [];
    private tools: string[] = [];
    private contact: Contact;
    constructor() {
        this.hobbies = ["Programming", "Music", "Playing Games"];
        this.technologies = ["React", "NextJS", "TailwindCSS", "React Query", "Typescript"];
        this.tools = ["Visual Studio Code", "Vite"];
        this.contact = {discord: "_Hixo"} 
    }
}
```

