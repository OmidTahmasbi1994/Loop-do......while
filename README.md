# Loop-do......while

#include <iostream>
#include <conio.h>

using namespace std;
int main()

{
	int n;
	int i=0;
	
	cout<<"Enter n:"<<endl;
	cin>>n;
	
	long sum = 0;
	
	do
	sum += i++ ;
	
	while(i <= n) ;
	
	cout<<"n : "<<n<<" sum : "<<sum;
	
	getch();
}
