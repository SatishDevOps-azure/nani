# nani
test cases
//Fibanocci Sequences
#include <iostream>
using namespace std;
int main()
{
int n1=0,n2=2,n3,i,number;
count<<"Enter the number of elements to be present in the series : ";
cin>>number;
count<<"Alternative fibanocci series is :";
count<<n1<<" ";
for((i=2;i<(number*2);i++)
{
n3=n1+n2;
n1=n2;
n2=n3;
if(i%2==0)
(
cout<<n3<<" ";
}
return 0;
}
