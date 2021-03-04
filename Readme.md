# Newman {{$randomWord}}

A collection to demonstrate a 'bug' in version < 5.2.2 or so. This bug has been solved since.

```
npm install -g newman@4.6.0

newman run '.\Newman randomWord.postman_collection.json' -e .\Newman_randomWord.postman_environment.json
```
or
```
npm install -g newman@4.5.4

newman run '.\Newman randomWord.postman_collection.json' -e .\Newman_randomWord.postman_environment.json
```

You'll se text like this generated : 'Credit Card Account', 'Mexican Peso Mexican Unidad de Inversion (UDI)'

In newer version this not append.

```
npm install -g newman@5.2.2

newman run '.\Newman randomWord.postman_collection.json' -e .\Newman_randomWord.postman_environment.json
```

```
["Georgia","killer","Bike","Orchestrator","Industrial","Synerg
  │ istic","synergistic","Tools","Incredible","invoice","Keyboard","navigate","Soap","Buc
  │ kinghamshire","Mandatory","Extensions","Frozen","JBOD","Soap","initiatives","Corporat
  │ e","Applications","COM","Account","Practical","bluetooth","Buckinghamshire","Product"
  │ ,"Practical","quantifying","capacitor","Agent","clicks-and-mortar","leading-edge","in
  │ dexing","Shoes","Intelligent","olive","Borders","expedite","Serbia","synthesize","rad
  │ ical","Table","middleware","yellow","blockchains","deposit","channels","neutral","Arc
  │ hitect","Forward","extensible","Tasty","Australian","multimedia","Bike","Soft","Outdo
  │ ors","Solutions","bypassing","parsing","Avon","Associate","green","rich","Cameroon","
  │ primary","Forward","Guinea","integrate","navigate","Metal","Gibraltar","Games","Ethio
  │ pian","Taiwan","withdrawal","Virtual","Buckinghamshire","sexy","Harbors","Rubber","En
  │ gineer","internet","yellow","payment","Fresh","Freeway","Kenyan","Gorgeous","Pizza","
  │ 1080p","Inlet","International","connect","synthesize","Shoes","optimize","Designer"]
```