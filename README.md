# Version-Control-Skills-Lab
This folder contains a notebook that takes an input from the user for their name and age and prints out a sentence stating their name and age - Vybhav Reddy
def calculate_water_intake():
   
    name = input("Enter your name: ")
    
    try:
        weight = float(input("Enter your weight in lbs: "))
        
        
        recommended_water_oz = weight * 0.5
        
        print(f"\nHello, {name}!")
        print(f"Based on your weight, your recommended daily water intake is approximately {recommended_water_oz:.1f} ounces.")
        
    except ValueError:
        print("Please enter a valid numeric value for your weight.")

calculate_water_intake()
