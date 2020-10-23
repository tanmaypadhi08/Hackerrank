#include <stdio.h>
#include <string.h>
#include <math.h>
#include <stdlib.h>
//Complete the following function.


void calculate_the_maximum(int n, int k) {
  //Write your code here.
int a=0,b=0,c=0,d,e,f;
for(int i=1;i<=n;i++)
{
    for(int j=i+1;j<=n;j++)
    {
        d=i|j;
        e=i&j;
        f=i^j;
        if(d<k)
        {
            if(b<d)
            b=d;
        }
        if(e<k)
        {
            if(a<e)
            a=e;
        }
        if(f<k)
        {
            if(c<f)
            c=f;
        }
    }
}
printf("%d\n%d\n%d",a,b,c);
}

int main() {
    int n, k;
  
    scanf("%d %d", &n, &k);
    calculate_the_maximum(n, k);
 
    return 0;
}
