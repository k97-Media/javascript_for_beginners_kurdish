# Lam Alqayada ema basi **Array** akain.

Wa am xalana rwn akainawa :

* Array chia ?
* Chon Array bakar benin ??
* Aw krdar yan shtanai atwanin lagal Array bikain chin ?

-----------------------------------------------------

### Array chia ?

**Array** : britia la kokrdnawai komalek , sht wak (Variable, String, Zhmara, Object yan Array tr) hemu la yak shwen ka wak snwqek yan Listek waia boman.


### Chon Array bakar benin ?

**Array** katek bakar denin ka komalek shtman habet w bmanawet hamu pekawa la tanha **Variable**ekda bn. Wa har katek wistman ba bakar henani nawi aw **Variable**a hamu aw shtanaman pekawa dast kawet.


**Array** bam shewa drwst akret :

```javascript

VARIABLE = [shti1, shti2, shti3]

nmwna:

const list = ['prtaqal', 'sew', 'limo', 1, 3, 5]
```

### Aw krdar yan shtanai atwanin lagal Array bikain chin ?

* **length :**  bakar det bo zanini zhmarai aw shtanai la **Array**akadan
    ```javascript
      const list = ['prtaqal', 'sew', 'limo', 1, 3, 5]
      list.length

      Anjam: 6
    ```
* **bakarhenani - `[zhmarai xana]` :** bakar det bo zanini nrxi aw shtai law xanadaia
  ```javascript
      const list = ['prtaqal', 'sew', 'limo', 1, 3, 5]
      list[0]

      Anjam: prtaqal

  ```
  ```javascript
      const list = ['prtaqal', 'sew', 'limo', 1, 3, 5]
      list[4]

      Anjam: 3
    ```
* **push() :** bakar det bo ziadkrdni shtek bo kotai **Array**aka
  ```javascript
      const list = ['prtaqal', 'sew', 'limo', 1, 3, 5]
      list.push('mn tazam')

      Anjam: ['prtaqal', 'sew', 'limo', 1, 3, 5, 'mn tazam']
  ```
  ```javascript
      const list = ['prtaqal', 'sew', 'limo', 1, 3, 5]
      list.push(200)

      Anjam: ['prtaqal', 'sew', 'limo', 1, 3, 5, 200]
  ```
* **pop() :** bakar det bo srinawai yak sht la kotai **Array**akawa
    ```javascript
      const list = ['prtaqal', 'sew', 'limo', 1, 3, 5]
      list.pop()

      Anjam: ['prtaqal', 'sew', 'limo', 1, 3]
    ```
* **shift() :** bakar det bo srinawai yak sht la saratai **Array**akawa
  ```javascript
      const list = ['prtaqal', 'sew', 'limo', 1, 3, 5]
      list.pop()

      Anjam: ['sew', 'limo', 1, 3, 5]
    ```
* **includes() :** bakar det bo zanini aia shtek lanaw **Array**aka haya yan na
  ```javascript
      const list = ['prtaqal', 'sew', 'limo', 1, 3, 5]
      list.includes('hanar')

      Anjam: False
  ```
  ```javascript
      const list = ['prtaqal', 'sew', 'limo', 1, 3, 5]
      list.includes('sew')

      Anjam: True
  ```
