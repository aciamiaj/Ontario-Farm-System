# Ontario-Farm-System

The Ontario Farm System demonstrates the management of farms and animals within those farms. It includes functionalities for adding animals to a farm, retrieving animal information, finding specific animals, removing animals, and obtaining the total number of animals.

## Code Overview
The provided code consists of the following components:

Farms: The code declares an array called ontarioFarm that can store up to 8 Farm objects. Each Farm represents a separate farm entity.

Animals: The code creates a List<Animal> called animals to store instances of animal objects.

Adding Animals: The code calls the Farm.AddAnimal() method, passing the animals list as an argument. This method adds animals to the list.

Printing Farm Name: The code uses Console.WriteLine() to print the name of the ontarioFarm.

Farm Methods: The code demonstrates the usage of various methods associated with the Farm class. These methods include Farm.GetAnimal(), Farm.GetName(), Farm.FindAnimal(), Farm.RemoveAnimal(), and Farm.GetNumAnimal(). These methods perform operations such as retrieving animal information, finding specific animals, removing animals, and obtaining the total number of animals.

## Usage
To use the Ontario Farm System, follow these steps:

Ensure that the necessary dependencies and classes (Farm and Animal) are implemented and available.

Create an array of Farm objects to represent the farms. In the provided code, an array named ontarioFarm with a size of 8 is used.

Create a List<Animal> to store instances of animal objects.

Use the appropriate methods of the Farm class to perform various operations on the animal list. These operations may include adding animals, retrieving animal information, finding specific animals, removing animals, and obtaining the total number of animals.

Utilize the Console.WriteLine() method to display the results or desired information.
  
## Notes
Please note that the provided code snippet is a simplified implementation to demonstrate the usage of the Farm Management System. In a real-world scenario, additional functionalities, error handling, and data persistence mechanisms may be required.
