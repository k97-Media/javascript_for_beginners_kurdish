# Lam Alqayada ema basi **DOM** akain.

Wa am xalana rwn akainawa :

* DOM chia ?
* DOM chon bakar det  ??

------------------------------------

### DOM:
Nawa drezhakai britia la **Document Object Model** wata hamw aw `Fail` w `Folder`anai ema bo `Website`ek drwsti akain. Hamuian lanaw `Object`ek ko akrenawa banawi **DOM**.

**DOM** ba dw shewa bakar det:

1. Pishandani lalaian `Browser` :
   Am jora sarakitring jora ka rozhana aibinin.
   `Browser`akaman aw `Object`a bakar denet takw aw `Page` yan `Website`aman pishan bat ka aikainawa.
   Ba kwrti wata pishandani `Website`aka lalain `Browser` bo bakarhenar.

2. Bakarhenani lalaian `Javascript`
   Twanai `Javascript` wa baheziakai lawadaia ka atwanet `DOM` wak har `Object`eki asai bakarbhenet. Amash wa akat ema btwanin la regai dastkari krdni `DOM` ba `Javascript` chandaha shty jyawaz w jwan la `Website`akaman bkain.

-------------------------------------------


### DOM chon bakardet ? 

Ema la regai `Javascript` atwanin dastkari `DOM` bkain.
Bamash ema twanaman abet 95% hamu `KOD`akani `HTML` yan `CSS` dastkari bkain. 


Bo awai btwanin dastkari har `TAG` yan `ELEMENT` yan `STYLE`ek bkain .
abet sarata aw shtai amanawet dastkari bkain diari bkain.

Awish bam dw rega :

1. Query Selector
   la `Query Selector` ema atwanin ba dw rega shtakan diari bkain
   
   * ba bakar henani `Class`
      Nawi Class wata ba nawi aw `class`ai ka drawa ba aw shtai amanawet diari bkain
        ```javascript
          const NAWI_VARIABLE = document.querySelector('.NAWI_CLASS')
        ```
    * ba bakar henani `ID`
      Nawi ID wata ba nawi aw `id`ai ka drawa ba aw shtai amanawet diari bkain
        ```javascript
          const NAWI_VARIABLE = document.querySelector('#NAWI_ID')
        ```
2. Get Element By
   la `Get Element By` ema atwanin bahoi nawi `ID` aw shtai amanawet shtakaman diari bkain
   ```javascript
    const NAWI_VARIABLE = document.getElementById('#NAWI_ID')
   ```



---------------------------

Har katek ema aw `ELEMENT yan TAG` ka amanawet diariman krd aw kata atwanin chandaha gorankari bkain teida ham la `HTML` yan `CSS`


1. Goranakan la HTML
  * Bo gorini nwsinikai
    ```javascript
      const tag = document.getElementById('#tag')
      tag.innerText = 'AW NWSINAI ATAWET LERA AINUSI'
    ```
  * Bo gorini TAGakani HTML
    ```javascript
      const tag = document.getElementById('#tag')
      tag.innerHTML = 'AW TAGai ATAWET DRWSTI BKAIT LERA AINUSI'
    ```
  * Bo ziadkrdni CLASS
    ```javascript
      const tag = document.getElementById('#tag')
      tag.classList.add('NAWI CLASS')
    ```
  * Bo srinawai CLASS
    ```javascript
      const tag = document.getElementById('#tag')
      tag.classList.remove('NAWI CLASS')
    ```
  * Bo zanini aia aw TAGa CLASSeki taibati haya yan na
    ```javascript
      const tag = document.getElementById('#tag')
      tag.classList.contains('NAWI CLASS')
    ```
2. Goranakan la CSS
   Ema ba ziadkrdni `.style` bo VARIABLEakaman atwanin har Shteki `CSS` bmanawet dastkari bkain.
    * Bo gorini rang
      ```javascript
        const tag = document.getElementById('#tag')
        tag.style.color = 'AW RANGAI ATAWET'
      ```
    * Bo gorini qabarai font
      ```javascript
        const tag = document.getElementById('#tag')
        tag.style.fontSize = 'AW QABARAI ATAWET'
      ```
    * Bo gorini pani
      ```javascript
        const tag = document.getElementById('#tag')
        tag.style.width = 'AW QABARAI ATAWET'
      ```

