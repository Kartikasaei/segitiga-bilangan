#include <iostream>
using namespace std;
int main(){
     
    int n;
    cout<<"Masukkan bilangan : ";
    cin>>n;
    
	if (n>=0 && n<10){
	   for (int i=n; i>=1; i--){
	   	cout<<endl;
           for (int j=1; j<=i; j++){
              cout<<i<<" ";
             }
}
}
   else{
   	
   	cout<<"Bilangan tidak sesuai!";
   }
   
	return 0;
}
