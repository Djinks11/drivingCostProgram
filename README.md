def main():
    milesPerGallon = float(input("Enter miles per gallon: "))
    dollarsPerGallon = float(input("Enter dollars per gallon: "))

    print(f"{DrivingCost(10.0, milesPerGallon, dollarsPerGallon):.2f}", end=" ")
    print(f"{DrivingCost(50.0, milesPerGallon, dollarsPerGallon):.2f}", end=" ")
    print(f"{DrivingCost(400.0, milesPerGallon, dollarsPerGallon):.2f}")
