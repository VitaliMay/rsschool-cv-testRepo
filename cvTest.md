```javascript

function getDecimal(n) {
   return +n.toString().replace(/^(.?\d+)/g, 0);
  }

  function getDecimal(n){
   if (n%1 === 0) return 0;
   return  +('0.' + n.toString().replace(/[-]?\d+[\.\,]/g, ''))
  }

```