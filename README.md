# CORDIC
Implementation of CORDIC algorithm in Python

# 1st Proof that is workin' fine:

(numerical example from random webpage)
![](https://i.gyazo.com/e49885e5552e10b6206660954da4a9c3.png) 

(results on our algorithm)
![](https://i.gyazo.com/b1641ad87696a21118e4dc571dec99a9.png)

# 2nd Proof that is workin' fine:

(numerical example from random webpage)
![](https://i.gyazo.com/410c5b79363f83c057ad540a22ddff83.png) 

(results on our algorithm)
![](https://i.gyazo.com/03f55cd39914ae839e223b92e02691c6.png)  


~~In CORDIC2.py the default number of iterations is 40 (N). It can be changed in lane 33: ~~

~~cos_val, sin_val = cordic_trig(beta)  //Default value = 40~~

~~OR~~

~~cos_val, sin_val = cordic_trig(beta, 3) //3 iterations~~

