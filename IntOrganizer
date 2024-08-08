#define tam 5
#include <stdio.h>

int main(void) {

  int n[tam], i;

  for (i=0; i<tam; i++){

    printf("Digite o %dº número: ", i+1);
    scanf("%i", &n[i]);
    
  }

  int temp;

  int tf = 0;
  
  do{
    tf = 1;
    for (i=1; i<tam; i++){
  
      if (n[i] < n[i-1]){
        temp = n[i];
        n[i] = n[i-1];
        n[i-1] = temp;
      }
    }

    for(i = 1; i<tam; i++){
      if(n[i] < n[i-1]){
        tf = 0;
      }
    }
  }while (tf == 0);

  for(i=0; i<tam; i++){
    printf("%i ", n[i]);
  }
  
  return 0;
}
