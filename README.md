print("Hei tervetuloa triviaan")
print("kirjoita vastauksesi aina pienellä ja yhteen")
ans=input("Oletko valmis pelaamaan (kyllä/ei): ")
score=0
total_q=5
if ans.lower() =="kyllä":
  print("1. python")
  print("2. kalle ja kala")
  print("3. kuho")
  print("4. jankkitankki")
  gk=input("Mikä on paras ohjelmointikieli? ")
  if gk=="1":
    print("Oikein")
    score+=1
  else:
    print("Väärin")

  print("1. Näytönohjain")
  print("2. Prosessori")
  print("3. RAM")
  print("4. Kaikki")
  gk=input("Mikä on lisäkortti joka välittää kuvaa näytölle? ")
  if gk=="1":
    print("Oikein")
    score+=1
  else:
    print("Väärin")

  print("1. 1000-sarja")
  print("2. 900-sarja")
  print("3. 600-sarja")
  print("4. 3000-sarja")
  gk=input("Mikä Nvidian näytönohjain sarjoista on uusin? ")
  if gk=="4":
    print("Oikein")
    score+=1
  else:
    print("Väärin")

  print("1.Tuomas")
  print("2. Kalle ja kala")
  print("3. Kuho")
  print("4. Jankkitankki")
  gk=input("Kuka on tehnyt tämän ohjelman? ")
  if gk=="1":
    print("Oikein")
    score+=1
  else:
    print("Väärin")

  print("1. ei tietenkään")
  print("2. ei")
  print("3. ON")
  gk=input("Onko Rust hyvä peli? ")
  if gk=="3":
    print("Oikein")
    score+=1
  else:
    print("Väärin")
print("Kiitos pelaamisesta sait",score, "viidestä kysymyksestä oikein.")
