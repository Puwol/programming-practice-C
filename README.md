# programming-practice-C

#include <iostream>
int main() {
  int n;
  scanf("%d", &n);
  
 
    if(n%2==0){
      for(int i=n; i>=1; i--){
    printf("%d-%d-%d = %d \n",i-1,i,i+1,i-1-i-i-1);
      }
      }
  else{ 
  for(int i=n; i>=1; i--){
    printf("%d+%d+%d = %d \n",i-1,i,i+1,i*3);}
  }
  }
