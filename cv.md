# Pronin Artem
### Trainee/Junior JS Developer
## Contacts
* Location: Khmelnytskyi, Ukraine
* Phone: +380952205895
* E-mail: heruwim25@gmail.com
_____
## My goals
_I want to study the __JS / Frontend Development__ сourse at __RSSchool__! And become a __Front-End developer!___
____


## Skills
+ HTML (base)
+ CSS (base)
+ Git (base)
+ JS (base)
+ C# (base)
+ Unity (base)
____


## Code Examples
```
function getMaxPrise(arraySearch) {
                let maxPriseArray = [];
                let maxPrise = arraySearch[0][3];
                for (let i = 0; i < arraySearch.length; i++){
                    if (arraySearch[i][3] > maxPrise){
                        maxPrise = arraySearch[i][3];
                    }
                }
                
                for (let i = 0; i < arraySearch.length; i ++){
                    if (arraySearch[i][3] === maxPrise){
                        maxPriseArray.push(arraySearch[i]);
                    }
                }
                
                return maxPriseArray;
            }
```