[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/tYncE4AO)
# quiz1_class_and_objects

## Instructions:
Please fill in the blank
```cplus
/*
* Name: Zachary Roland
*/

// Question: Create a C++ class representing a car with attributes like model, year, and color. Include a method to display car details.
// Answer: --------------------------------------- here

#include <iostream>
#include <string>

class Car {
private:
    std::string model;
    int year;
    std::string color;
public:
    void std::string setModel(std::string carModel)
    {
        model = carModel;
    }
    void int setYear(int carYear)
    {
        year = carYear
    }
    void std::string setColor(std::string carColor)
    {
        color = carColor;
    }

    void std::string getModel()
    {
        return model;
    }
    void int getYear()
    {
        return year;
    }
    void std::string getColor()
    {
        return color;
    }


    void displayDetails() {
        std::cout << "Model: " << model << ", Year: " << year << ", Color: " << color << std::endl;
    }
};

int main() {
    Car myCar;
    std::string myCarModel;
    int myCarYear;
    std::string myCarColor;

    std::cout << "Enter the car model: " << endl;
    cin >> myCarModel;
    std::cout << "Enter the car year: " << endl;
    cin >> myCarYear;
    std::cout << "Enter the car color: " << endl;
    cin >> myCarColor;

    myCar.setModel(myCarModel);
    myCar.setYear(myCarYear);
    myCar.setColor(myCarColor);

    myCar.displayDetails();

    return 0;
}

```

