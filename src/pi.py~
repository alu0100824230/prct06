
#! encoding: UTF-8
def aproxpi(fin):
  if n>0:
    suma=0
    pi=3.1415926535897931159979634685441852
    for i in range(1,fin+1):
      a=(i-1.0)/fin
      b=(i+0.0)/fin
      xi=(i-0.5)/fin
      fxi=4.0/(1.0+xi*xi)
      suma+=fxi
    aprox=suma/fin
  return aprox

l=[]
veces=int(raw_input('Introduzca el número de veces: '))
n=int(raw_input('Introduzca el número de subintervalos: '))
for i in range(1,veces+1):
  n=n*i
  s=aproxpi(n)
  print "El valor aproximado de PI es: %11.10f" % s
  l=l+[s]
print l
    