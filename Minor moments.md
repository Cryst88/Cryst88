#include <iostream>

using namespace std;

int main (void) {
   int age = 17;
   cout << "Enter your age: ";
   cin >> age;
   if (age < 18) {
   cout << " You're a minor";
   }else {
   cout << " You're not a minor";
}
return 0;
}
    
