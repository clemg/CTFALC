# CTFALC
Android Lock Pattern Crack originally made for a CTF


## Installation:
```shell
$ git clone https://github.com/clemg/CTFALC
```

## Usage:
```shell
$ python3 CTFALC.py ./gesture.key.sample 
```

## Example output:
```shell
[i] Looking for key b21e9299bc501c403717d4c950954468a496c1ef... 

trying length 3 patterns...  nothing
trying length 4 patterns...  nothing
trying length 5 patterns...  nothing
trying length 6 patterns...  nothing
trying length 7 patterns...  nothing
trying length 8 patterns...

[!] GESTURE FOUND!!! 04137658 



Follow these steps to unlock the phone:
-------------
| 1 | 3 |   |
-------------
| 4 | 2 | 7 |
-------------
| 6 | 5 | 8 |
------------- 


[i] Time: 1.0687787532806396s
```

Credits:
+ Phack CTF for the challenge
+ [sch3m4](https://github.com/sch3m4/androidpatternlock) for the "steps to follow" idea
