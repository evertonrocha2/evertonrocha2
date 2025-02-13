const mySkills = {
  languages: ["JavaScript", "TypeScript", "PHP", "Python", "Java", "C#"],
  databases: ["MySQL", "DBeaver"],
  libraries: ["React", "MUI", "Tailwind CSS"],
  frameworks: ["Next.js", "Node.js", ".NET", "Vite"]
};

const profileDescription = `
Hi, I'm Everton Silva, welcome to my GitHub.

- I'm studying ${mySkills.languages.join(", ")}, and more.
- Having focus and discipline is the foundation.
- Fascinated by problem solving and everything involving technology.
- My goal? To work internationally, leveraging my skills to contribute to global progress.

My Skills:

Main Stacks:
- Languages: ${mySkills.languages.join(", ")}
- Databases: ${mySkills.databases.join(", ")}
- Libraries: ${mySkills.libraries.join(", ")}
- Frameworks: ${mySkills.frameworks.join(", ")}
`;

console.log(profileDescription);
