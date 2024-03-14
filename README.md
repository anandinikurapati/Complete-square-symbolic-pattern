# Complete-square-symbolic-pattern
# Approach - 1
for i in range(3):
  for j in range(3):
    print("*",end=" ")
  print()
# Appraoch - 2
a = []
for i in range(3):
  x = []
  for j in range(3):
    x.append("*")
  a.append(x)
#print(a)
for i in a:
  print(*i,sep=" ")
# Approach - 3
for i in range(3):
  print("* "*3)
