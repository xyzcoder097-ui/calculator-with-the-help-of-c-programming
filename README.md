#include<stdio.h>
int main(){
    int a;
    int b;
    int c;
    while(1){
    printf("Enter a number:\n");
    scanf("%d",&a);
    printf("Enter a number:\n");
    scanf("%d",&b);
    printf("Add\n,sub\n,multiply\n,divivde\n,exit\n ");
    scanf("%d",&c);
    if(c==1){
        printf("Addition of a and b %d\n",a+b);
        
    }else if(c==2){
        printf("subtraction of a and b %d\n",a-b);
    }else if(c==3){
        printf("multiplication of a and b%d\n",a*b);
    } 
    else if(c==4){
        
       printf("division of a and b %d\n",a/b);
    }
    else if(c==5){
        printf("existing calculator");
        break;
    } else{
        printf("invslid choice:");
    }}
    return 0;
    }
    return 0;
}
