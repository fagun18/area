#include<stdio.h>
int main()

{
    double  a, b, c, t, o, z, s, r;
    scanf("%lf %lf %lf", &a, &b, &c);

    t= (0.5 * a * c),
    o= (3.14159 * c * c),
    z= (((a + b) / 2) * c),
    s= (b * b),
    r= (a * b);
    printf("TRIANGULO: %0.3lf\nCIRCULO: %0.3lf\nTRAPEZIO: %0.3lf\nQUADRADO: %0.3lf\nRETANGULO: %0.3lf\n", t, o, z, s, r);

    return 0;

}
