# Codigos
#include <stdio.h>

int def1() {
    int r;

    for(r = 1; r <= 100; r++) {
        printf("%d,", r);
    }
    
    printf("\n");
    return 0; 
}

int def2(){
    int p;
    int soma = 0;

    for(p = 10;p <= 1000; p++){
        if(p % 2 != 0){
            soma = soma + p;
            
        }

    }

    printf("%d ",soma);
    printf("\n");

}

int def3() {
    int t;

    for(t = 1; t <= 200; t++) {
        if(t % 3 == 0 && t % 10 != 3) {
            printf("%d, ", t);
        }
        
    }
    printf("\n");
    return 0; 
}

int main() {
    def1();
    def2();
    def3();

    return 0; 
}
