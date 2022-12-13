### Proje Detayı: https://app.patika.dev/courses/python-temel/proje

```python 

# İlk Proje

l = [[1,'a',['cat'],2],[[[3]],'dog'],4,5]
duzenlenen = []

def duzlestirme(liste):
    for i in liste:
        if isinstance(i,list):
            duzlestirme(i)
        else:
            duzenlenen.append(i)

duzlestirme(l)
print(duzenlenen)



# İkinci Proje


l = [[1, 2], [3, 4], [5, 6, 7]]
l = l[::-1]

for i in range(len(l)):
    l[i]=l[i][::-1]

print(l)

