# Lab-1.40
#include <iostream>
#include <string>

using namespace std;

int main() {
  
  const float TAX_RATE = 0.055;
  float price;
  float tax;
  float total;
  string item;
  
  // Display prompts and get input.
  cout << "Item description (no spaces):  ";
  cin >> item;
  cout << "Item price: $";
  cin >> price;
  
  // Perform the calculations.
  tax = price * TAX_RATE;
  total = price * tax;

  // Display the results.
  cout << item << "   $" << price << endl;
  cout << "Tax   $" << tax << endl;
  cout << "Total   $" << total << endl;
}
