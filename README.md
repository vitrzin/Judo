# Judo
 class TJudo_rec
  strukturo Judo spremenimo razred (class)
  izdelamo metode:
   print() - ki nam vrne String z vsebino razreda
   get_sel()  prebere trenutno stanje parametra 'select'
   set_sel()
   change_sel()

 class TJudo_array
  cilj: uporabiti vector namesto c_array-a
   vector<TJudo_rec> jarr;
   s tem dobimo podatek o številu zapisov v podatkovni bazi
  velikost vector-ja se samodejno prilagaja količini podatkov
  metode:
   save()
   load()
   size()
