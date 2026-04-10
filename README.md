# Aulinha_de_Revisão


1. a.#include <stdio.h>

void main()
{
     int x = 10;
     int * p;
    
     p = &x;
    
    printf("%d",&x);
}

b.#include <stdio.h>

void main()
{
     int x = 10;
     int * p;
    
     p = &x;
    
    printf("%d",*p);
}

c.#include <stdio.h>

void main()
{
     int x = 10;
     int * p;
    
     p = &x;
    
    printf("%d",&p);
}

2.#include <stdio.h>

void main()
{
    int a = 5, b = 15;
    int *p1, *p2;
    p1 = &a;
    p2 = &b;
    
    *p1=100;
    *p2=200;
    
    printf("%d , %d",a,b);
}

3.#include <stdio.h>

void main()
{
    float a,b,r;
    float *p1, *p2;
    
    printf("digite um valor ");
    scanf("%f",&a);
    printf("digite um outro valor ");
    scanf("%f",&b);
    
    p1=&a;
    p2=&b;
        r=*p1+*p2;
    
    printf("%2.f",r);
}

4.
