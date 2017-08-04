`id:000000,sig:11,src:000020,op:arith8,pos:0,val:-21`

```
#0  ex1 (w=0x7ffacc127218, k=0x0, i=0x7ffde0252558, n=<optimized out>, f=1) at src/kx.c:824
#1  0x0000000000420b8c in ex0 (v=<optimized out>, k=<optimized out>, r=<optimized out>) at src/kx.c:688
#2  0x0000000000424465 in ex_ (a=0x7ffde02525e0, r=0) at src/kx.c:664
#3  0x000000000042426a in ex (a=<optimized out>) at src/kx.c:672
#4  0x000000000041cd70 in line (f=<optimized out>, a=<optimized out>, n=<optimized out>, p=<optimized out>) at src/kc.c:283
#5  0x000000000041db1a in lines (f=<optimized out>) at src/kc.c:246
#6  0x0000000000409ec0 in load (s=0x7ffde0252e1d "output/k-1/crashes/id:000000,sig:11,src:000020,op:arith8,pos:0,val:-21") at src/c.c:85
#7  0x000000000041be77 in args (n=<optimized out>, v=<optimized out>) at src/kc.c:90
#8  0x0000000000447066 in main (argc=9, argv=0x0) at src/main.c:7
```



`id:000002,sig:11,src:000001+000321,op:splice,rep:4`
```
#0  unpool (r=<optimized out>) at src/km.c:184
#1  kallocI (k=<optimized out>, r=<optimized out>) at src/km.c:153
#2  kalloc (k=<optimized out>, r=<optimized out>) at src/km.c:158
#3  newK (t=<optimized out>, n=<optimized out>) at src/km.c:141
#4  0x000000000042b959 in promote (a=0x7efcfeb9acc0) at src/ko.c:105
#5  0x00000000004451c5 in joinI (a=<optimized out>, y=0x7efcfeb9af80) at src/vg.c:623
#6  0x00000000004452a1 in join (x=<error reading variable: Cannot access memory at address 0x0>, y=0xffffffffffffffff) at src/vg.c:629
#7  0x00000000004217fa in vf_ex (q=<optimized out>, g=<optimized out>) at src/kx.c:484
#8  0x000000000041f1a4 in dv_ex (a=0x7efcfeb9acc0, p=0x7efcfeb985f0, b=<optimized out>) at src/kx.c:401
#9  0x0000000000423656 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:981
#10 0x0000000000422db2 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:987
#11 0x0000000000422db2 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:987
#12 0x0000000000422db2 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:987
#13 0x0000000000422d34 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:951
#14 0x0000000000422db2 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:987
#15 0x0000000000422db2 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:987
#16 0x0000000000422d34 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:951
#17 0x0000000000422db2 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:987
#18 0x0000000000422db2 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:987
#19 0x0000000000422db2 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:987
#20 0x0000000000422db2 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:987
#21 0x0000000000422db2 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:987
#22 0x0000000000422db2 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:987
#23 0x0000000000422d34 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:951
#24 0x0000000000422db2 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:987
#25 0x0000000000422db2 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:987
#26 0x0000000000422d34 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:951
#27 0x0000000000422db2 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:987
#28 0x0000000000422db2 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:987
#29 0x0000000000422d34 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:951
#30 0x0000000000422db2 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:987
#31 0x0000000000422d34 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:951
#32 0x0000000000422d34 in ex2 (v=<optimized out>, k=<optimized out>) at src/kx.c:951
#33 0x00000000004248e4 in ex1 (w=<optimized out>, k=<optimized out>, i=<optimized out>, n=<optimized out>, f=2) at src/kx.c:829
#34 0x0000000000420b8c in ex0 (v=<optimized out>, k=<optimized out>, r=<optimized out>) at src/kx.c:688
#35 0x0000000000424465 in ex_ (a=0x7fffa43386a0, r=0) at src/kx.c:664
#36 0x000000000042426a in ex (a=<optimized out>) at src/kx.c:672
#37 0x000000000041cd70 in line (f=<optimized out>, a=<optimized out>, n=<optimized out>, p=<optimized out>) at src/kc.c:283
#38 0x000000000041db1a in lines (f=<optimized out>) at src/kc.c:246
#39 0x0000000000409ec0 in load (s=0x7fffa4339e1a "../post-min/id:000002,sig:11,src:000001+000321,op:splice,rep:4") at src/c.c:85
#40 0x000000000041be77 in args (n=<optimized out>, v=<optimized out>) at src/kc.c:90
#41 0x0000000000447066 in main (argc=0, argv=0xffffffffffffffff) at src/main.c:7
```


