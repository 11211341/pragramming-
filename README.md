import datetime
dailySpecials=("Spaghetti","Macaroni & Cheese", "Meatloaf", "Fried Chicken")
weekendSpecials=("Lobster","Prime Rib","Parmesan-Crusted Cod")
print("My Healthy Eats Delivery")
if today == "Friday" or today =="Saturday" or today =="Sunday":
print("The weekend specials include:")
for item in weekendSpecials:
print(item)
else:
print("The weekday spcials include: ")
for item in dailySpecials:
print(item)
print(f"Pricing specials change in {daysLeft} days")
