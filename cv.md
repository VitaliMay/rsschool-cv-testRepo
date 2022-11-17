# Vitali Majewski

### Contact information:
**Phone:** +375 29 6-906-306  
**E-mail:** mvt30@mail.ru  
**GitHub:** VitaliMay

----

### About Me
I am an excellent team worker  


----
### Skills
* HTML (in progress)<br>
* CSS (in progress)<br>
* JavaScript (in progress)<br>

----
### Code example:
[**Bingo Card KATA from CODEWARS**](https://www.codewars.com/kata/bingo-card)  ![](./assets/svg/codewars_button_icon_151901.png)<br>
*And my first recursion :)*<br>

```javascript

function getCard() {
  let BINGO = []
  for (let i = 0; i < 5; i++){
    BINGO[i] = 'B' + (Math.floor(Math.random() * (15)) + 1)
    BINGO[i+5] = 'I' + (Math.floor(Math.random() * (15)) + 16)
    BINGO[i+5+4] = 'N' + (Math.floor(Math.random() * (15)) + 31)
    BINGO[i+5+4+5] = 'G' + (Math.floor(Math.random() * (15)) + 46)
    BINGO[i+5+4+5+5] = 'O' + (Math.floor(Math.random() * (15)) + 61)
  }
  if (BINGO.length === [...new Set(BINGO)].length) return BINGO;
  return getCard()
}

```

-----
### Languages:
* English - (A2) Pre-Intermediate
* Russian - Native
* Polish - Basic
* Ukrainian - Basic
