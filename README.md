# reversestring

word=input("enter string: ")
reverse=""
length=len(word)
while length>0:
    reverse=reverse+word[length-1]
    length=length-1
print(reverse)    
