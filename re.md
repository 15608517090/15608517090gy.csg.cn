# CTF 网鼎杯-MISC-minified-WriteUp

CTF 网鼎--MISC--minified--WriteUp

0通道为空值

![img](.img/webp-16970139056257.webp)

image.png

分别保存 green blue alpha 的0通道值

三者分别进行异或操作

![img](.img/webp-16970139056258.webp)



![img](.img/webp-16970139056259.webp)

image.png



![img](.img/webp-169701390562610.webp)

image.png

![img](.img/webp-169701390562611.webp)

image.png

![img](.img/webp-169701390562612.webp)

image.png

![img](.img/webp-169701390562613.webp)

image.png

Alpha plane 0和green plane 0通道进行XOR

即可得到flag