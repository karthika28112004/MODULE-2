# Ex.No:1
# Ex.Name:Write A CPP Program to allocate memory dynamically for a double array. (Note: p_array = new type [size]; )
## Aim:
To write A CPP Program to allocate memory dynamically for a double array.(Note: p_array = new type [size]; )

## Algorithm:

1.Start the program.

2.Input the size of the array from the user.

3.Dynamically allocate memory for a long array using long* p_array = new long[size];

4.Display confirmation that the array has been created.

5.Read array elements from the user and store them in the allocated memory.

6.Print all stored array elements in sequence.

7.Release the allocated memory using delete[] p_array; and display confirmation, then end the program.




## Program:
```
#include <iostream>
using namespace std; 
class var_space
{
  public:
  void allocateSpace()
  {
    char *ptr = new char;
    cin >> *ptr;
    cout << "Character Value is : " << *ptr;
  }
};
int main()
{
   var_space s;
   s.allocateSpace();
   return 0;
}
```
## Output:

<img width="1329" height="269" alt="image" src="https://github.com/user-attachments/assets/9436d352-39af-4933-9cc6-d5ad040e8fc4" />


## Result:
Hence the program is executed successfully.
