# ANTON ISHKIN

### Contact:
*E-mail:* avtew@outlook.com  
*GitHub:* [avtew](https://github.com/avtew)  
*Discord:* [avtew](https://discordapp.com/users/963009110461259826)   
*Telegram:* [avtew](https://t.me/avtew)  

### About Me:
I'm 35 years old. I love tech, computers and cats.

### Skills:
* HTML5
* CSS and Sass
* Core JS
* Git
* Grafic design (Figma, Photoshop, Illustrator)

### Projects:
[Landing](https://rolling-scopes-school.github.io/avtew-JSFEPRESCHOOL/portfolio)  
[Image Gallery](https://rolling-scopes-school.github.io/avtew-JSFEPRESCHOOL/image-galery)  
[Game](https://rolling-scopes-school.github.io/avtew-JSFEPRESCHOOL/memory-game)  
[Web Page](https://rolling-scopes-school.github.io/avtew-JSFE2022Q1/shelter/pages/main/)  
[Keyboard](https://avtew.github.io/virtual-keyboard/)  

### Code Example:
The goal of this exercise is to convert a string to a new string where each character in the new string is "(" if that character appears only once in the original string, or ")" if that character appears more than once in the original string. Ignore capitalization when determining if a character is a duplicate.  
```
function duplicateEncode(word) {
  let result = '';
  let splitArray = word.toLowerCase().split('');
  for (i = 0; i < splitArray.length; i++) {
    let count = 0;
    let x = splitArray[i];
    for (j = 0; j < splitArray.length; j++) {
      if (splitArray[j] === x) {
        count++;
      }
    }
    if (count === 1) {
      result += '(';
    } else {
      result += ')';
    }
  }
  return result;
}
```

### Work Experience
* Worker  
*Machine-building company "Petrozavodskmash"*
* Engineer  
*State Atomic Energy Corporation "Rosatom"*
* CNC Operator  
*Machine-building company "Avangard"*

### Education:
* Vocational college 
* Courses:
    * Course of lectures "Lean Manufacturing"
    * Education program "CNC Operator"
    * RSSchool JavaScript/Frontend Pre-School
 
### English Level:
Iintermediate (A2)  
