// the result
#include<iostream>
using namespace std;


int main() {
	int k;
  

  while(cin>>k){
    int n = k-1;
    
	  for(int a=1; a<= n; a++){
		  for(int j=1; j <=n-a; j++){
			  cout << " ";	
	  	}
		  for(int j=1; j<=2*a-1; j++){
		  	cout << "*";
		  }
		  cout<< endl;
	  }
    for(int a=1; a<= n-1; a++){
		  for(int j=1; j<=a; j++){
		  	cout << " ";	
		  }
		  for(int j=1; j<=2*n-1-2*a; j++){
		  	cout << "*";
		  }
		  cout<< endl;
	  }
  }
	
	
return 0;	
}








/* first try:
#include <iostream>
using namespace std;

int main() {
  int k;
  cin >> k;
  int K = k*2-3;
  int i=0;
  
  while(i <= K){
     if(i < K/2){
      for(int a=0; a<= i*2+1; a++){
        cout << "* ";
        }
      i = i+1;
      cout << endl;
    }
    else if(i >= K/2){
      for(int a=0; a<=23-2*i; a++){
        cout << "* ";
      }
     i = i+1;
      cout << endl;
    }
    
  }
  

  
  return 0;
  }
*/


/* second try:
#include <iostream>
using namespace std;

int main() {
  int k;
  cin >> k;
  double K = k*2-3;  //K是總行數,邊長
  int i=0; //i 是第幾行數
  
  while(i < K/2){
    for(int a=k-2; a>1; a--){
      cout<< " ";
    }
    for(int a=1; a<=2*i+1; a++){
      cout<<"*";
    }
    i = i+1;
    cout << endl;
  }
  
  while(i<K){
   for(int a=k-2; a>=1; a--){
      cout<< " ";
    }
    for(int a=0; a<=2*i+1; a++){
      cout<<"*";
    }
    i = i+1;
    cout << endl;
  }
  

  return 0;
  }
*/



/* third try:
#include<iostream>
using namespace std;

int main() {
	int n;
	cin >> n;
	
	for(int a=1; a<= n; a++){
		for(int j=1; j <=n-a; j++){
			cout << " ";	
		}
		for(int j=1; j<=2*a-1; j++){
			cout << "*";
		}
		cout<< endl;
	}
	
	
	
	return 0;	
}
*/
