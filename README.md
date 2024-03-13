# Python_proje
"""1. sorunun çözümü"""
def duzeltilmis_liste(mix_liste):
    duzeltilmis_liste=[]
    for i in mix_liste:
        if isintance(i,list):
            duzeltilmis_liste.extend(uzeltilmis_liste(i))
        else:
            duzeltilmis_liste.append(i)
    return duzeltilmis_liste        
"""************************"""
"""2. sorunun çözümü"""
def tersine_cevir(liste):
    yeni_liste = []
    for eleman in liste[::-1]:
        if isinstance(eleman, list):
            yeni_liste.append(tersine_cevir(eleman))
        else:
            yeni_liste.append(eleman)
    return yeni_liste

  """*********************"""""
