# fibonacci

def fib():
  p = 0 
  s = 1
  while s < 10:
    yield s
    p, s = s, s+p

[x for x in fib()]
