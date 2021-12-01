# Cplus2.0-sumofnum-
sum of x and y

#include <iostream>
using namespace std;
int main()
{
  int x,y;
  int sum;
  cout<<" Type a number: ";
  cin>>x;
  cout<<" Type a number: ";
  cin>>y;
  sum=x+y;
  cout<<" Sum is " << sum;
  return 0;
}
  /*output:
  
  Type a number:90
  Type a number:50
  sum is 140
  */
  
#include <iostream>
using namespace std;
int main()
{
  string firstName="Iren\t"; //puydi pod 1000
  string lastName="Salazar\t"; //tapos 2000
  cout<<firstName+lastName;
  return 0;
}
   /*output:
  
  Iren Salazar */
