# Lam Alqayada ema basi **If statments(Agarakan)** akain.

Wa am xalana rwn akainawa :

* If statments chia ?
* Chon If statments bakar benin ??
-----------------------------------------------


### If statments ( Agarakan )

Wata **Agarakan** bakar det bo briar dan lasar shtek. Bo nmwna alein agar bayani taqikrdnawa bet awa axwenin agar taqi krdnawash nabet naxwenin.

-------------------------------------------

### Boolean

**Boolean** yakeka la grngtrin aw shtanai la agarakan bakari denin . Brtia la dw jor nrx ka **True** wata rast yan **False** wata hala. Ba pei am dw jora nrxa ema atwanin briar lasar hamw shtek bdain

----------------------------
#### Xaleki grng

La **Javascript** wa zorbai zmanakani **Programming**
Nishanai `=` manaiaki jyawazi haya la aw manai ema la rozhana bakari denin.

1. `=`
   Yak nishanai `=` bakardet bo pedani **nrx** ba shtek
   bo nmwna:
   `X=5`
   ema lera nrxi 5 adain ba `X`
2. `==`
   Dw nishanai `=` ba dwai yak bakardet wak yaksanai rozhana wata bo zanini aia dw sht yaksann
   bo nmwna:
    ```
      aia 5 == 5 ?
      bale
    ```
    ```
      aia 5 == 10 ?
      naxer
    ```
--------------------------
### Sadatrin shewa

Agar x yaksan bw ba 5 bnwsa rasta
Agar yaksan nabu bnusa halaia

```javascript
  let x = 5
  if(x == 5){
    rasta
  }
  else{
    halaia
  }

  Anjam:
  rasta
```

```javascript
  let x = 3
  if(x == 5){
    rasta
  }
  else{
    halaia
  }

  Anjam:
  halaia
```
---------------------------

### bakarhenani chand agarek pekawa

```javascript
  let x = 3
  if(x == 5){
    rasta
  }
  else if(x == 3){
    x yaksana ba 3
  }
  else{
    halaia
  }

  Anjam:
  x yaksana ba 3
```
-----------------------

### briar dan bapei chand anjamek pekawa

Ema handek kat amanawet chand shtek pekawa sair bkain wa agar rast bwn enja karaka bkain.
yan agar rast nabun karaka nakain.

Bo nmwna :

* `la rozhi nawroz agar xor bw (wa) sayaraka kari krd achin bo sairan`

  Lerada ema briar aiain ka bchin bo sairan katek dw sht rast bn:
  1. xor bet
  2. sayaraka ish bkat

  agar am dw shta hardwki rast bw enja achin bo sairan, agar yakekian rast nabu awa nachin.

  Am krdara pei awtret (and) wa nishanai `&&` bo bakardet
  ```javascript
    let x = 3
    let y = 4
    if(x == 3 && y == 4){
      rasta
    }
    else{
      halaia
    }

    Anjam:
    rasta
  ```

  ```javascript
    let x = 3
    let y = 6
    if(x == 3 && y == 4){
      rasta
    }
    else{
      halaia
    }

    Anjam:
    halaia
  ```

* `la bazar agar prtaqal (yan) moz habu awa miwa akrm`
  lerada ema briar aiain ka miwa bkrin katek yakek la shtakan rast bet:
  1. Prtaqal habet
  2. Moz habet
  
  Kawata agar har yakek law dwana rast bw awa miwa akrin agar rast nabw awa miwa nakrin

  Am krdara pei awtret (or) wa nishanai `||` bo bakardet

  ```javascript
    let x = 3
    let y = 4
    if(x == 3 || y == 4){
      rasta
    }
    else{
      halaia
    }

    Anjam:
    rasta
  ```

  ```javascript
    let x = 3
    let y = 5
    if(x == 3 || y == 4){
      rasta
    }
    else{
      halaia
    }

    Anjam:
    rasta
  ```