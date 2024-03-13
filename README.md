# Python_proje

def duzeltilmis_liste(mix_liste):
    duzeltilmis_liste=[]
    for i in mix_liste:
        if isintance(i,list):
            duzeltilmis_liste.extend(uzeltilmis_liste(i))
        else:
            duzeltilmis_liste.append(i)
    return duzeltilmis_liste        
