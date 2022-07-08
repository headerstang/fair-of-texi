# fair-of-texi

--python code--
car_type = "sedan"
drive_range = 20
days = 2

if car_type == "sedan":
    fair = 1500
    per_km = 20
    
elif car_type == "compact_suv":
    fair = 1300
    per_km = 15

    
elif car_type == "suv":
    fair = 1600
    per_km = 25
    
else: 
    fair = 1250
    per_km = 12
    
if drive_range > 0:
    final_price = drive_range * per_km 
    
print("price")
print(final_price)

if days >= 1:
    final_amount = drive_range * per_km + fair
    print("The final amount: ")
    print(final_amount)
