# Pattern---5-Equilateral-Pyramid-

    *
   ***
  *****
 *******
*********





#include<iostream>
using namespace std;

int main()
{
    int n=5;
    for(int i=1;i<=n;i++)
    {
        //printing leading spaces
        for(int j=1;j<=(n-i);j++)
        {
            cout<<" ";
        }
        //per row 2 stars increasing (2*i-1[for the first row only 1 star must be printed so 2*i-1])
        for(int k=1;k<=(2*i-1);k++)
        {
            cout<<"*";
        }
        cout<<endl;
    }
}
