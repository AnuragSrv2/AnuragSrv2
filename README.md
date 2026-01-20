class Developer {
  constructor() {
    this.name = "Abhishek Kumar";
    this.role = "Aspiring Full-Stack Developer";
    this.education = "Final Year BCA Student";
    this.interests = ["Full-Stack Development", "AI/ML", "DSA"];
    this.passion = "Solving real-world problems with technology";
  }
  info() {
    return `
Name      : ${this.name}
Role      : ${this.role}
Education : ${this.education}
Interests : ${this.interests.join(", ")}
Passion   : ${this.passion}`;
  }
}
const me = new Developer();
console.log(me.info());
