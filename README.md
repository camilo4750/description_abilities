### Hi Everyone 👋

I´m Camilo Alarcón

I am a guy passionate about constantly learning about programming, my mission is to strive and always give my best to meet my goals and grow a lot.
Personally and professionally, I like to drink coffee while programming, I always try to deal with my difficulties as calmly as possible and break 
my problems down into different parts.

"Divide and conquer"; 💯

a little more about me..!

const Skills = {
  Frontent: ["Html", "Css", "Bootstrap", "React", "Javascript"],
  Backend: ["Php", "Python", "NodeJs", "Express"],
  Databases: ["Mysql", "MongoDB"],
  Challenge: [
    "Improve and explore new skills, overcome my rivalries and be better every day than the previous one",
  ],
};

function EspecificacionSkills({ Frontent, Backend, Databases, Challenge }) {
  console.log(
    `💪 I´m currently Working whith ${Frontent[0]}, ${Frontent[1]}, ${Frontent[2]}, ${Backend[0]} ${Backend[1]}, ${Databases[1]}`
  );
  console.log(
    `📈 I´m currently learning ${Frontent[4]}, ${Backend[2]} con ${Backend[3]}, ${Databases[1]}`
  );
  console.log(`😄 Everything is always with the same purpose: ${Challenge}`);
}

EspecificacionSkills(Skills);
