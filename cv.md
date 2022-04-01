# __[rsschool-cv-html](https://SergKnyazev.github.io/rsschool-cv/)__

---
# __Serg Knyazev__

![Serg Knyazev](/images/avatar-sk.png)

---

### __Contacts__

- Location : __Voronezh, Russia__
- Phone : __+7 (911) 219-32-27__
- Email : serg.knyazev77@gmail.com
- GitHub : [SergKnyazev](https://github.com/SergKnyazev)
- Discord : __SergKnyazev#4238__

---

### __About Me__
🙋 Hi, I'm Sergey Knyazev. I work as an information security specialist. I 💖 Javascript. This programming language is beautiful. I would like to work in the IT field. 

---

### __Skills__
- HTML
- CSS / SASS
- JavaScript
- ReactJS
- Node.js (Basic)
- SQL (Basic)
- Git (Basic + )

---

### __Code Example__
```javascript
function isMAC48Address(n) {
  const MAC_ADRESS_CHARS = '0123456789ABCDEF';

  let arrMacAdressElements = n.split('-');

  if (n.length !== 17 || 
      arrMacAdressElements.length !== 6) return false;

  for (let elem of arrMacAdressElements) {
    if (
      elem.length !== 2 ||
      !MAC_ADRESS_CHARS.includes(elem[0]) ||
      !MAC_ADRESS_CHARS.includes(elem[1])
    )
      return false;
  }
  return true;
}
```

---