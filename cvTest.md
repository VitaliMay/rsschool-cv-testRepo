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