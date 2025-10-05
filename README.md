```js
const fhyrox = {
  name: "Fhyrox",
  age: 15,
  location: "Istanbul, Turkey",
  role: "Backend Developer",
  stack: [
    "Node.js", "JavaScript", "TypeScript",
    "React", "Next.js", "Express",
  ],
  projects: ["Arktik"],

  contact: {
    github: "github.com/fhyrox",
    email: "fhyroxx@gmail.com",
  }
};

function sayHi(dev) {
  console.log(`👋 Hi, I'm ${dev.name}, a ${dev.role} based in ${dev.location}.`);
  console.log(`💻 Currently working on: ${dev.projects.join(" & ")}`);
}

sayHi(fhyrox);
```
