# ecc-point
Elliptic Curve Cryptosystem for Learning Cryptography

Usage

Change BASE to whatever you want
Pass in two numbers for initialization
G_Point = ECC_Point(8, 11)

+ operator overloading
P_Point = G_Point + G_Point

* operator overloading and show_val() method
(G_Point * 4).show_val()
P_Point.show_val()
