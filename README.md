#include<iostream>
using namespace std;
int main(){
int a;
int arr[100];
int n=0;
cin>>a;

while(a>1){
	
	arr[n]=a%2;
	a/=2;
	n++;
	
}
arr[n]=a;
for(int i=0;i<=n;i++){
	cout<<arr[n-i];
	
}

return 0;	
}
