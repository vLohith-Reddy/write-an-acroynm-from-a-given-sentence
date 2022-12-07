# write-an-acroynm-from-a-given-sentence
input = str(input("enter a phrase: "))
text = input.split()
a= " "
for i in text:
    a = a+str(i[0]).upper()
print(a)
#output:
enter a pharse python
ans:PYTHON
