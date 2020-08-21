# YAML

YAML scripting represents configuration data and in applications where data is being stored or transmitted.

#### Comments in YAML
```bash
The lines starts with "#" will be considered as commented line
```

#### Creating a Key Value Pair
```bash
Key1: Value1
Key2: Value2
...
```

#### Creating a Array/List
* Ordered Collection of Data
```bash
Data:
- value1
- value2
- value3
```

#### Creating a Dictionary/Map
* Unordered Collection of Data
* To store the properties of an item in a key-value pair.
```bash
Dictionary:
  key1: value1
  key2: value2
...
```

#### List inside a List
```bash
Property:
- List1:
  - value1
  - value2
  
- List2:
  - value1
  - value2
...
```

#### Dictionary inside a Dictionary
```bash
Dictionary:
  key1: value1
  key2: 
    key1: value1
    key2: value2
  Key3: value3
...
```

#### Dictionary/Map inside a List
```bash
List:
- Dictionary1:
    key1: value1
    key2: value2
    
- Dictionary1:
    key1: value1
    key2: value2
...
```


