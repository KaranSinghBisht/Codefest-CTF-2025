## Description

Because Events Head said "NO CATS"

## Writeup

Well struggled with this one until figured out have to use passwords from rockyou.txt
I downloaded the rockyou (which is not required, thx to kn1gh7's writeup)
and hence ran

```bash
stegseek chall.jpg ./rockyou.txt
```

Alternatively you can also do

```bash
stegseek --crack -sf chall.jpg -wl rockyou.txt
```

## Flag

`CodefestCTF{573gh1de_ch4ll_m30w}`

![catsolve.png](./assets/catsolve.png)
