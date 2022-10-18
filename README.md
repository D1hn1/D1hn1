```python
from myself import *

ME = {
  "name" : "DANI",
  "about" : {
    "location" : "Málaga",
    "age" : 17
  },
  "studies" : {
    "location" : "IES BEZMILIANA",
    "studiying" : "MICROINFORMÁTICA Y REDES"
  }
}

print("Hey there!!")
info = input("Enter what you wanna know ~$ ")
if info == "name": print(ME["name"])
elif info == "about": print(ME["about"]["location"], ME["about"]["age"])
elif info == "studies": print(ME["studies"]["location"], ME["studies"]["studiying])
```

