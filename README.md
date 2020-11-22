#include <iostream>

using namespace std;

class Car {
    public:
        string Brand;
        string Color;
        string Model;
        string Seats;
        string Trunk;
};

int main () {
    Car object1; 
    object1.Brand="Mercedes";
    object1.Color="Silver";
    object1.Model= "Cla";
    cout<<"\nBrand = "<<object1.Brand;
    cout<<"\nColor = "<<object1.Color;
    cout<<"\nModel = "<<object1.Model;
    Car object2;
    object2.Seats="Leather";
    object2.Trunk="Medium";
    cout<<"\nSeats = "<<object2.Seats;
    cout<<"\nTrunk = "<<object2.Trunk;
}
