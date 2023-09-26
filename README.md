# Car-fuel-consumption
distance_traveled = float(input("Distance traveled (in km): "))
fuel_consumed = float(input("The amount of fuel consumed (in liters): "))

fuel_efficiency = fuel_consumed / (distance_traveled / 100)

if fuel_efficiency < 7:
    print("The car is low consumption.")
else:
    print("The car is high consumption.")
