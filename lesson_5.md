# Lam Alqayada ema basi **Object** akain.

Wa am xalana rwn akainawa :

* Object chia ?
* Chon Object bakar benin ??
-----------------------------------------------

### Object chia ?

**Object** : Britia la ko krdnawai chand zaniariak ka taibatn ba yak sht la yak shwenda. La regai ( KEY ) wa ( VALUE ) wak .

Bo nmwna wak farhangek waya to wshakan diari akait teida lagal watakanian. 


KEY = wshakan ( abet daima tak yaxwd shaz bn)
VALUE = nrxakan atwanret har shtek bn

----------------------------------------------

### Chon Object bakar bhenin ?

Ema Object bakardenin bo penasakrdni sthek laregai zaniariakani. wa dwatr aw zaniariana bakar denin baw shewai pewistmana.

Bam shewa **Object** drwst akret :

``` javascript
  JORI VARIABLE   NAWI VARIABLE = {
    KEY_1 : VALUE_1,
    KEY_2 : VALUE_2,
    KEY_3 : VALUE_3
  }
```

Nmwna : 

``` javascript
  const qwtabi = {
    naw : "Korak",
    pol : 5,
    wanaiKautw : "birkari"
  }
```


Bam shewa nrxi taza ziad akain :

``` javascript
  NAWI_OBJECT["KEY taza"] = NRXI TAZA

  Nmwna :
  const qwtabi = {
    naw : "Korak",
    pol : 5,
    wanaiKautw : "birkari"
  }

  qwtbai["wanaiDarchu"] = "Kurdi"

  anjam :

  qwtabi = {
    naw : "Korak",
    pol : 5,
    wanaiKautw : "birkari",
    wanaiDarchu : "Kurdi"
  }
```
yan

``` javascript
  NAWI_OBJECT.KEY_taza = NRXI TAZA

  Nmwna :
  const qwtabi = {
    naw : "Korak",
    pol : 5,
    wanaiKautw : "birkari"
  }

  qwtbai.wanaiDarchu = "Kurdi"

  anjam :

  qwtabi = {
    naw : "Korak",
    pol : 5,
    wanaiKautw : "birkari",
    wanaiDarchu : "Kurdi"
  }
```

-----------------------------------

Bam shewa nrxakan dastkari akren :

``` javascript
  NAWI_OBJECT["KEY"] = NRXI TAZA

  Nmwna :
  const qwtabi = {
    naw : "Korak",
    pol : 5,
    wanaiKautw : "birkari"
  }

  qwtbai["pol"] = 10

  anjam :

  qwtabi = {
    naw : "Korak",
    pol : 10,
    wanaiKautw : "birkari",
  }
```

Yan

``` javascript
  NAWI_OBJECT.KEY = NRXI TAZA

  Nmwna :
  const qwtabi = {
    naw : "Korak",
    pol : 5,
    wanaiKautw : "birkari"
  }

  qwtbai.pol = 10

  anjam :

  qwtabi = {
    naw : "Korak",
    pol : 10,
    wanaiKautw : "birkari",
  }
```

