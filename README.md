# Function to calculate the cost of driving a given number of miles
def DrivingCost(drivenMiles, milesPerGallon, dollarsPerGallon):
    costMiles = drivenMiles * (1.0 / milesPerGallon) * dollarsPerGallon
    return costMiles

def main():
    # Get fuel efficiency and gas price from user
    milesPerGallon = float(input("Enter miles per gallon: "))
    dollarsPerGallon = float(input("Enter dollars per gallon: "))

    # Calculate and display trip costs for 10, 50, and 400 miles
    print(f"{DrivingCost(10.0, milesPerGallon, dollarsPerGallon):.2f}", end=" ")
    print(f"{DrivingCost(50.0, milesPerGallon, dollarsPerGallon):.2f}", end=" ")
    print(f"{DrivingCost(400.0, milesPerGallon, dollarsPerGallon):.2f}")
