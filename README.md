# LA-10

class Vehicle():
    def __init__(self, brand, model, fuel_type):
        self.brand = brand
        self.model = model
        self.fuel_type = fuel_type
        
    def describeVehicle(self):
        print(f"{self.brand} has {self.model} with {self.fuel_type}")


class Motorcycle(Vehicle):
    pass

honda = Motorcycle("Honda","click 123", "gasoline.")
honda.describeVehicle()

class Car(Vehicle):
    pass

honda = Car("Toyota","vigo", "electric.")
honda.describeVehicle()
