# Lam Alqayada ema basi **Switch statments** akain.

Wa am xalana rwn akainawa :

* Switch statments chia ?
* Chon Switch statments bakar benin ??

------------------------------------

### Switch statment : 
  ba haman shewai **If stamement** bakar det wata bo kar krdn lagal agarakan . Balam la **Switch Statment** ema atwanin chand agarek w halateki zor la yak kat check bkain.

--------------------------------------------------

### Sheway bakarhenan:

Ema abet **Variable**ekman habet ka chawderi goran la nrxakai bkain


```javascript
  let NAWI_VARIABLE = NRX
  switch(VARIABLE KA CHAWDERI AKAIT){
    case NRX_1:
      aw shtai atawet bikai wata kodakan lera anwsit
      break;
    case NRX_2:
      aw shtai atawet bikai wata kodakan lera anwsit
      break;
    case NRX_3:
      aw shtai atawet bikai wata kodakan lera anwsit
      break;
    case NRX_4:
      aw shtai atawet bikai wata kodakan lera anwsit
      break;
  }
```

Nmwna:

```javascript
  let x = 5
  switch(x){
    case 1:
      nrxi x 1
      break;
    case 2:
      nrxi x 2
      break;
    case 8:
      nrxi x 8
      break;
    case 5:
      nrxi x 5
      break;
  }

  anjam: nxri x 5
```

```javascript
  let x = 8
  switch(x){
    case 1:
      nrxi x 1
      break;
    case 2:
      nrxi x 2
      break;
    case 8:
      nrxi x 8
      break;
    case 5:
      nrxi x 5
      break;
  }

  anjam: nxri x 8
```

-----------------------------------------

Ema atwanin `default` bo kotai ziad bkain agar katek hich kam law nrxana nabun aw kata aw shtai la `default` ainusin bakardet

Nmwna :

```javascript
  let x = 15
  switch(x){
    case 1:
      nrxi x 1
      break;
    case 2:
      nrxi x 2
      break;
    case 8:
      nrxi x 8
      break;
    case 5:
      nrxi x 5
      break;
    default :
      nrxi x buni nia
      break;
  }

  anjam: nxri x buni nia
```