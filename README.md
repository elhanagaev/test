def is_numbr(str):
  try: 
  float(str)
  return True
 except ValueError:
  return False
a = '123.456'
print(is_number(a))

True
