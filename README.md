# FIND-THE-SUM-OF-EVEN-AND-ODD-
find the sum of even and odd in given number 
#include<iostream>
using namespace std;

int main() {
	int n,sum=0,add=0,rem;
        while(n>0){
		rem=n%10;
            if(rem%2==0){
			sum=sum+rem;
            }
            else
                add=add+rem;
            n=n/10;
        }
    cout<<sum<<" "<<add;
    return 0;
	
}
