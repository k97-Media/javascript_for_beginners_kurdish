# Lam Alqayada ema basi **STRING** akain.

Wa am xalana rwn akainawa :

* String chia ?
* Chon String bakar benin ??
* Aw krdar yan shtanai atwanin lagal String bikain chin ?

-----------------------------------------------------

### String chia ?

**String** : britia la jorek la jorakani **Data** wa bakar det bu nusini asaii wak wsha yan komala wshaiak. Yaxwd har shtek ka bmanawet wak nusineki assai bakari bhenin.

**String** ba dw shewa anwsret :

1. ```javascript
   " Nwsinaka lera anwsit "
     
     Nmwna:

   " Mn Kurdm "
   ```
2. ```javascript
   ' Nwsinaka lera anwsit '
     
     Nmwna:

   ' Mn Kurdm '
   ```


### Chon String bakar denin ?

**String**akan bakar den bo pishan dani nusinek etr aw nwsina tanha pitek yan chand pitek bet yaxwd rsta yan chand rstaiak.



### Aw krdar yan shtanai lagal String bikain chin ?


* **Length :** bakar det bo zanini zhmarai **Pit** yan aw **Charachter**anai lanaw **String**aka haya.
  ```javascript
    const string = 'mn'
    string.length

    Anjam : 2

    --------------------
    const string = 'javascript'
    string.length

    Anjam : 10
   ```

* **bakarhenani - [zhmarai xana] :** bakar det bo zanini aw pita yan aw shtai law xanadaia
  ```javascript
    const string = 'mn'
    string[0]

    Anjam : m

    --------------------
    const string = 'javascript'
    string.[5]

    Anjam : c
   ```

* **indexOf() :** bakar det bo zanini zhmarai xanai aw shtai labaini kawanakan ainusin

  ```javascript
    const string = 'mn'
    string.indexOf('m')

    Anjam : 0

    --------------------
    const string = 'javascript'
    string.indexOf('c')

    Anjam : 5
   ```
* **toLowerCase() :** bakar det bo krdni hamu pitakan ba **Small**

  ```javascript
    const string = 'Mn'
    string.toLowerCase()

    Anjam : mn

    --------------------
    const string = 'JAVASCRIPT'
    string.toLowerCase()

    Anjam : javascript
   ```
* **toUpperCase() :** bakar det bo krdni hamu pitakan ba **Capital**

  ```javascript
    const string = 'Mn'
    string.toUpperCase()

    Anjam : MN

    --------------------
    const string = 'javascript'
    string.toUpperCase()

    Anjam : JAVASCRIPT
   ```
* **includes() :** bakar det bo zanini aia aw shtai aixaina baini kawanakan la naw **String**aka haya yaxwd na.
    ```javascript
    const string = 'Mn'
    string.includes('o')

    Anjam : False
  --------------------------
    string.includes('M')

    Anjam : True
   ```
