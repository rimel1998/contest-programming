# contest-programming

http://www.progkriya.org/gyan/basic-number-theory.html

https://www.youtube.com/watch?v=nTKFgx0yBb4
# string compare:
https://www.programiz.com/c-programming/library-function/string.h/strcmp
# how to use end of file
#include <stdio.h>

int main()
{
    int x,y,i;
    unsigned long long a=1,b=1,c;

    while(scanf("%d%d",&x,&y)!= EOF)
    {

    a=1;
    b=1;
    for(i=1; i<=x; i++)
    {
        a=a*i;
    }
    for(i=1; i<=y; i++)
    {
        b=b*i;
    }
    c=a+b;
    printf("%llu\n",c);
    }

    return 0;
}

