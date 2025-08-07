```jsx
import Me from "me";
import Charlie from "./Charlie";

class About extends Me.Component {
  constructor() {
    super();

    this.info = {
      nickname: "Chang",
      nationality: "PH_fil",
      male: true,
      loves: ["Coding", "Tech", "Fast Bikes", "NU Metal"],
      currentFocus: ["Flutter", "Startup Project"],
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

<p align="center">
<a 
href="https://www.linkedin.com/in/charlie-g-pandacan" target="_blank"><img alt="LinkedIn" 
src="https://img.shields.io/badge/linkedin-%2312100E.svg?&style=for-the-badge&logo=linkedin&logoColor=blue" /></a>
<a 
href="https://stackoverflow.com/users/2612959/charlie" target="_blank"><img alt="StackOverflow" 
src="https://stackoverflow-badge.vercel.app/?userID=2612959" /></a> 
<a 
href="https://github.com/gitChang" target="_blank"><img alt="Github" 
src="https://img.shields.io/badge/GitHub-%2312100E.svg?&style=for-the-badge&logo=Github&logoColor=white" /></a>
</p>
