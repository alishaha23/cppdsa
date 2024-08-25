# cppdsa
#include<iostream>
using namespace std;
void arr3(int *arr,int n){
for(int i=0;i<n;i++){
cout<< arr[i]<<",";


}
cout<<endl;

}
int main(){


int arr[]={2,4,5,7,6};
int n=sizeof(arr)/sizeof(int);
int arr2[n];
for(int i=0;i<n;i++){

int j=n-i-1; //j =original array i=copyarray2

arr2[i]=arr[j];

}
for(int i=0;i<n;i++){
    arr[i]=arr2[i];
{
 arr3(arr,n);

return 0;


}
