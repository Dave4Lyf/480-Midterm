#include <iostream> 
#include <iomanip> 
int main() 
{ 
const int arraySize = 10; 
int a[arraySize] = {2, 6, 4, 8, 10, 12, 89, 68, 45, 36}; 
int i, hold; 
std::cout << "data items in original order\n"; 
for (i=0;i < arraySize; i++)
std::cout << std::setw (4) << a[i]; 
for (int pass=0; pass < arraySize -1; pass++) 
for(i=0; i<arraySize-1; i++) 
if(a[i] >a[i+1]) { 
hold = a[i]; 
a[i]=a[i+1]; 
a[i+1]=hold; 
} 
std::cout << "\nData items in ascending order\n"; 
for(i=0; i<arraySize; i++) 
std::cout << std::setw (4) << a[i]; 
std::cout << std:: endl; 
return 0; 
} 
