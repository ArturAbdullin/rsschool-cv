# Artur Abdullin

## Position
Junior Frontend Developer

## Contacts
- **Location:** Saint-Petersburg, Russia
- **Phone:** <a href="tel:+79062763010">+7(906)276-30-10</a>
- **Telegram:** [Artur Abdullin](https://t.me/ArturAbdullin)
- **E-mail:** artur.abdullin@gmail.com
- **GitHub:** [ArturAbdullin](https://github.com/ArturAbdullin)

## About me
Hi! I'm Artur Abdullin and I'm interested in web development. For almost 10 years I was an educator in higher education and an engineer working on control algorithms for precision electromechanical systems. Now I've been studying Frontend oriented courses on different platforms for almost a year. I'm open for new knowledge and constantly working on myself.

Aside from programming I like to play guitar. Here is my [band page](https://vk.com/vypole) :blush:

## Skills and Proficiency
- **Hard:**
  + HTML5, CSS/SASS
  + JavaScript (ES6+)
  + TypeScript
  + webpack
  + Git, GitHub
  + Figma
- **Soft:**
  + Critical thinking
  + Learnability
  + Punctuality
  + Adaptability
  + Creativity
  + Teamwork
  + Sociability

## Code example
```
// Knuth-Morris-Pratt search algorithm: failure function

function kmpFailureFunction(needle: string): number[] {
  let T: number[] = [0];
  let j: number = 0;
  let i: number = 1;

  while (i < needle.length) {
    if (needle[j] === needle[i]) {
      T[i] = j + 1;
      i++;
      j++;
    } else if (j === 0) {
      T[i] = 0;
      i++;
    } else {
      j = T[j - 1];
    }
  }

  return T;
}
```

## Education
- 2011-2014: ITMO University, PhD in system analysis, control and information processing.
- 2009-2011: ITMO University, Master's degree in automation and control.
- 2005-2009: ITMO University, Bachelor's degree in electrotechnics, electromechanics and electrotechnologies.

## Languages
- Russian - native
- English - B2-C1 (Completed a special program "English as a medium of instruciton" at Boston University CELOP Jan 27 - Feb 14, 2020)
