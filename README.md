# -python-secondstring.py
def reverse(s): 
  str = "" 
  for i in s: 
    str = i + str
  return str
  
s = str (input('Please enter a sentence : '))
  
a = (reverse(s))

print (a[::2])
