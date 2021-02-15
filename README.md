# optional-1
#include <iostream>
#include <iomanip>
using namespace std;

int main() {
cout << setprecision(1) << fixed;
 double x;
 double y;
 double h = 5;
 double w = 10;

 cout << "Enter an x-coordinate for a point:" << endl;
 cin >> x;
 cout << "Enter a y-coordinate for a point:" << endl; 
 cin >> y;


 if ((x <= w/2) && (y <= h/2)) {
   cout << "The point(" << x  << "," << y << ") is in the rectangle." << endl;
 }
 else {
   cout << "The point(" << x << "," << y << ") is not in the rectangle." << endl;
 }



}
