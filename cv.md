 # ZHOMART TURAROV

<img src="assets/turarov.jpg" width="200" height="200" />

### Ph.D. candidate, TU Kaiserslautern, Germany

## Contacts

* **Phone:** +49-178-0000000
* **Email:** j.turarov@gmail.com
* **Discord:** Zhomart (@TurarovZhM)
* [LinkedIn](https://www.linkedin.com/in/zhomart-turarov-b45580131/)
* [GitHub](https://github.com/turarovzhm)

## Education
* **_2016-2018_** _Masters degree in Applied Mathematics and Computer Science. M.V.Lomonosov Moscow State University, Moscow, Russia_
* **_2016-2018_** _Bachelor. Mathematical and Computer Modeling. L.N. Gumilyov Eurasian National University, Nur-Sultan, Kazakhstan_

## Languages
* Kazakh
* Russian
* English (B2)
* Deutsch (B1)

## IT skills
* Python
* MS SQL
* HTML5, CSS3
* JavaScript Basics
* SAS (Ent. Guide, Miner)
* Git, GitHub
* LaTex

## Code example: _binary_search in Python_
```
def binary_search(arr, x):
    lo = 0
    hi = len(arr) - 1
    mid = 0

    while lo <= hi:
        mid = (hi + lo) // 2
        if arr[mid] < x:
            lo = mid + 1
        elif arr[mid] > x:
            hi = mid - 1
        else:
            return mid
    return -1
```
