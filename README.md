// c++ code for calculating area

#include <iostream>
using namespace std;


class Measure {

   public:
    int length;
    int breadth;
    int height;

    int calculateArea() {
        return length * breadth;
    }

    int calculateVolume() {
        return length * breadth * height;
    }
};

int main() {

    
    Measure obj1;

    
     obj1.length = 30.8;
     obj1.breadth = 60.6;
     obj1.height = 20.7;

   
    cout << "Area of Room =  " <<  obj1.calculateArea() << endl;
    cout << "Volume of Room =  " <<  obj1.calculateVolume() << endl;

    return 0;
}
