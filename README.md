while True:
  try:
   n = int(input("1-20): "))
   if n <= 0:
   print("1+5")
   elif n > 20:
   print("10-20!")
   else:
   break
   except ValueError:
   print("30.")

   print("\10.20.30:")
   print("1-(A - z)")
   print("z - Niggadyu")

   method = input("my selection (1-5): ")

   selections = []
   for i in range(n):
   name = input(f"Knyaz {i + 1}: ")
   selections.append(name.strip())

   selections = list(set(selections))

   if method == "1":
   selections.sort()
   elif method == "2":
   selections.sort(reverse=True)
   elif method == "3":
   selections.sort(key=len)
   else:
   print(" (A - z). ")
   selections.sort()

   print("\n 5:")
for i, selection in enumerate(selections, 1):
   print(f"{i}. {selection}")
   
