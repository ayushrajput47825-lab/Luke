# Luke
#include &lt;stdio.h> int main() {     int a,b,temp;     int *p1,*p2;      printf("Enter two numbers:");     scanf("%d%d",&amp;a,&amp;b);      p1 = &amp;a;     p2 = &amp;b;      temp = *p1;     *p1 = *p2;     *p2 = temp;      printf("\nAfter Swapping:\n");     printf("a=%d\n",a);     printf("b=%d\n",b);      return 0; }
