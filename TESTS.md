# initialization test
## setup
Connected 
```mermaid
flowchart LR
  b004 --> b075 
  b075 --> r[100R between pinns 1 and 10 of J2]
  
```
## results
initialization works on a standard PoE switch.


# current test
## setup
Connected
```mermaid
flowchart LR
  b004 --> b075 
  b075 --> r[variable resistor between pinns 1 and 10 of J2]
  
```
## results
| current | voltage |
|--|--|
|1A|5V|
|2A|4.9V|
|2.6A|4.9V|

