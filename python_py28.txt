szavak = ['ajtó','tojás','Ottó','Tamás', 'tép','Tesla','alma','python']
lista=[]

for i in szavak:
    if i[0] =='t' or i[0] =='T':
        lista.append(i)
    
print(lista)