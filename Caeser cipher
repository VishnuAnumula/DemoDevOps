import string
dict={}
for i in range(len(string.ascii_letters)):
    dict[string.ascii_letters[i]]=string.ascii_letters[i-3]
v='I am Iron Man'
for i in range(len(v)):
    if v[i] in dict:
        print(v[i].replace(v[i],dict[v[i]]),end='')
        continue
    print(v[i],end='')
