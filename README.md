# C.

#include <stdio.h>
/*
float main() {
    float n1;
    float n2;
    float n3;
    float media;
    printf("Digite o primeiro numero:", n1);
    scanf("%f", &n1);
    printf("Digite o segundo numero:", n2);
    scanf("%f", &n2);
    printf("Digite o terceiro numero:", n3);
    scanf("%f", &n3); 
    media = (n1+n2+n3)/3;
    printf("A média é:%f", media);
    
    return 0;
    
}
*/
------------------------------------------
/*
int main(){
    int n1;
    int n2;
    int soma;
    int media;
    char tecla;
    
    printf("digite o 1 numero: ");
    scanf(" %d", &n1);
    printf("digite o 2 numero: ");
    scanf(" %d", &n2);
    printf("Digite S para somar, e qualquer outra letra para média: ");
    scanf(" %c", &tecla);
    
    if(tecla == 's'){
        soma = n1 + n2;
        printf("a soma vale:%d", soma);
        
    }else{
        media = (n1+n2)/2;
        printf("a média é: %d", media);
        
        
    }
        
    
    return 0;
    
}
-------------------------------------
int main() {
    int A;
    int B;
    int result;
    char simb;
    
    printf("Digite um numero:", A);
    scanf(" %d", &A);
    printf("Digite o segundo numero: ", B);
    scanf(" %d", &B);
    printf("Digite + para somar, - para subtração, D para divisão e M para multiplicação.", simb);
    scanf(" %c", &simb);
    
    do{
        
        printf("digite um comando valido!");
        scanf(" %c", &simb);
        
        }while(simb != '+' && simb != '-' && simb != 'D' && simb != 'M');
        
        if(simb =='+'){
            result = A+B;
            printf("A soma é: %d", result);
        }else if(simb =='-'){
            result= A-B;
            printf("A subtração é: %d", result);
        }else if(simb =='D'){
            result= A/B;
            printf("A divisão é: %d", result);
        }else if(simb =='M'){
            result= A*B;
            printf("A multiplição é: %d", result);
        }else{
            printf("Tecla não reconhecida, tente novamente.");
        }
        
    
    return 0;
}
