# Ilya Radchenko
### Junior Frontend Developer

---

### Contact information:
* **Phone:** +79054738245
* **E-mail:** chop.chop.rock.pop@gmail.com
* **Telegram:** @ilya_rrr

---

### About Me:

I am 23 years old, working as a freelancer. Participated in WordSkills. I study web development, UI/UX. I design websites and write a blog about frontend.

---

### Skills:

* HTML5, CSS3
* JavaScript
* Git, GitHub
* Figma, Adobe Photoshop, Illustrator
* VS Code, vim
* Windows OS, Linux(Ubuntu)

---

### Code examples:

**Strip Comments KATA from CODEWARS:** *Complete the solution so that it strips all text that follows any of a set of comment markers passed in. Any whitespace at the end of the line should also be stripped out.*

```
function solution(input, markers) {
  return input.split('\n')
  .map(  line => {
      let indx = -1;
      indx = Math.max(
        ...markers.map( marker => indx = line.indexOf(marker) ? line.indexOf(marker): -1 )
      )
      return indx >= 0 ? line.slice(0, indx).trim() : line
  })
       .join('\n');
 
};
```

---

### Education:

* Engineering Technician. College of Digital and Pedagogical Technologies, Tyumen
    + Additive Technology

* Courses:
    + HTML Academy
    + FreeCodeCamp
    + CS50 lectures

### Languages:
* English - Intermediate
* Ukrainian - Upper-intermediate
* Russian - Native



