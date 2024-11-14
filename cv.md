## **Raman Milashevich**

### **Junior Frontend Developer**

---

### **Contact Information**

* **Location:** Warsaw, Poland
* **Phone:** +48 577 753 711
* **Email:** Roma.Milashevich@gmail.com
* **GitHub:** [RamanMilashevich](https://github.com/RamanMilashevich)
* **LinkedIn:** [Raman Milashevich](https://www.linkedin.com/in/raman-milashevich-331951221/)

## About Me

_I am an aspiring frontend developer passionate about creating modern and interactive web applications. I have experience working with core frontend languages and technologies such as JavaScript, CSS, Sass, HTML, Git, and JSON. I strive for continuous learning and development to create more efficient and cross-browser solutions._ 

## Skills and Proficiency:

* **HTML5, CSS3, Sass**
* **JavaScript, Angular**
* **jQuery**, **Gulp**, **Datajs**
* **Git, GitHub**
* **VS Code, IntelliJ IDEA**
* **Figma, Adobe Photoshop, InDesign**

## Code Example:

_ROT13 is a simple letter substitution cipher that replaces a letter with the letter 13 letters after it in the alphabet. ROT13 is an example of the Caesar cipher.

Create a function that takes a string and returns the string ciphered with Rot13. If there are numbers or special characters included in the string, they should be returned as they are. Only letters from the latin/english alphabet should be shifted, like in the original Rot13 "implementation"._

```javascript
  function rot13(message) {
      const input = 'ABCDEFGHIJKLMNOPQRSTUVWXYZabcdefghijklmnopqrstuvwxyz';
      const output = 'NOPQRSTUVWXYZABCDEFGHIJKLMnopqrstuvwxyzabcdefghijklm';
      let encoded = '';

      for (let i = 0; i < message.length; i++) {
          const char = message[i];
          const index = input.indexOf(char);

          if (index === -1) {
              // Character not found in input (not a letter), keep unchanged
              encoded += char;
          } else {
              // Rotate the letter according to ROT13
              encoded += output[index];
          };
      };

      return encoded;
  };
```