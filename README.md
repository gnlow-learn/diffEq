# diffEq
differential equations (맛보기)

## Diffeq-web

https://martinjrobins.github.io/diffeq-web/
```
in = [a, b, c]
a { 1 }
b { 1 }
c { 1 }
u_i {
  s = 0.9,
  i = 0.1,
  r = 0,
}
dudt_i {
    dsdt = 0,
    didt = 0,
    drdt = 0,
}
F_i {
    dsdt,
    didt,
    drdt,
}
G_i {
    -a * s * i,
    a * s * i + b * i * r - c * i,
    -b * i * r + c * i,
}
out_i {
    s,
    i,
    r,
}
```