print("Программа для расчета налога на автотранспорт в Казахстане!")

mrp = 3450

while(True):

  print("введите объем двигателя:")
  v = float(input())
  
  print("Введите год производства автомобиля или год завоза автомобиля в Казахстан")
  year = int(input())
  
  if v < 1.1:
    print(1 * mrp)
  
  elif v >= 1.1 and v <= 1.5:
    print(2 * mrp)
  
  elif v >= 1.5 and v <= 2:
    print(3 * mrp)
  
  elif v >= 2 and v <= 2.5:
    print (6 * mrp)
  
  elif v >= 2.5 and v <= 3:
    print (9 * mrp)
  
  elif v >= 3 and v <= 4 and year <=2013:
    print (15 * mrp)
  
  elif v > 4 and v <= 4 and year <=2013:
    print (117 * mrp)
  
  elif v > 3 and v <= 3.2 and year >=2014:
    print (35 * mrp)
  
  elif v > 3.2 and v <= 3.5 and year >=2014:
    print (46 * mrp)
  
  elif v > 3.5 and v <= 4 and year >=2014:
    print (66 * mrp)
  
  elif v > 4.0 and v <= 5.0 and year >=2014:
    print (130 * mrp)
  
  elif v > 5.0 and year >=2014:
    print (200 * mrp)
