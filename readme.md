Opening the index.html
---
Please note I used import maps to quickly add vue js. Please use Chromium-based browsers to have vue js work. 
Since I also didn't use any frontend build system. i added data.json directly on Vue initialization (line 149 in index.html)

###### Bonus points
* added animation on scroll
* Explain why the result of `('b' + 'a' + + 'a' + 'a').toLowerCase()` is `banana`.
  * 'b' + 'a' = 'ba'
  * 'a' + + 'a' = NaN
  * NaN + 'a' = 'NaNa'
  * .toLowerCase() results to 'banana'

