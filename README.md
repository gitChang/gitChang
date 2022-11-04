<!--### Hi there 👋 -->

<!--
**gitChang/gitChang** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

```jsx
import Me from "me";
import Charlie from "./Charlie";

class About extends Me.Component {
  constructor() {
    super();

    this.info = {
      nickname: "Chang",
      place: "Tagum, Philippines",
      male: true,
      loves: ["Coding", "Tech", "Fast Bikes", "NU Metal"],

      technologies: {
        backEnd: ["Ruby", "Python", "NodeJS"],
        frontEnd: ["AngularJS", "ReactJS", "Bootstrap", "JavaScript"],
        database: ["MSSQL", "PostgreSQL", "MongoDB"],
        devOps: ["Linux", "Selenium", "NGINX", "PaaS"],
      },

      others: ["PenTest", "Customization"],
      currentFocus: "Azure",
      funFact: "Coding will soon be as important as reading.",
    };
  }

  render() {
    return (
      <>
        <Charlie who={this.info} />
      </>
    );
  }
}
```
