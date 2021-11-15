/*  OOC Lecture 02 */

// Exercise 
#include <iostream>
using namespace std;

int main() 
{
  int length, width, perimeter;
  cout << "Input the length :";  // Get the input of length
  cin >> length;   // input length
  cout << "Input the width :";   // Get the input of width
  cin >> width;    // input width

  perimeter = 2*(length + width); // calculate the perimeter

  cout << "Perimeter :" << perimeter << endl; // Display the perimeter

  return 0; 
}





/*  OOC Lecture 02 */

// Exercise 1
#include <iostream>
#include <iomanip>
using namespace std;

int main() 
{
  float radius, area;
  cout << "Input the radius of the circle :"; // Get the radius as input
  cin >> radius; // input radius
  
  area = 3.14* radius* radius ; // calculate the area

  cout << "Area of the circle :" << setiosflags (ios::fixed) << setprecision(2) << area << endl; // Display the area of the circle

  return 0; 
}






/*  OOC Lecture 02 */

// Exercise 2

#include <iostream>
#include <iomanip>
using namespace std;

int main() 
{
  float tPrice, discount;
  cout << "Input the total price :"; // Get the total price as input
  cin >> tPrice; // input total price
  
  if(tPrice > 10000)
  discount = 0.25* tPrice ; // calculate the discount

  else 
  if (tPrice > 5000) 
  discount = 0.15* tPrice ; // calculate the discount

  else 
  if (tPrice > 3000)
  discount = 0.1* tPrice ; // calculate the discount

  cout << "Discount :" << setiosflags (ios::fixed) << setprecision(2) << discount << endl; // Display the discount

  return 0; 
}





/*  OOC Lecture 02 */

// Exercise 3

#include <iostream>
using namespace std;

int main() {
 
int count=1000;

while ( count >=100 )  // while loop
{
     cout << count << endl;
     count = count - 100;
}

do			// do-while loop
{
     cout << count << endl;
     count = count - 100;
}while ( count >=100 );

for(int count=1000; count >=100 ; count = count - 100)  // for loop
    cout << count << endl;


return 0;
}





