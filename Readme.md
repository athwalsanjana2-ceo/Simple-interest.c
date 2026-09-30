#include <stdio.h>
#include <conio.h>
void main()
{
    int p, r, t;
    float si;
    clrscr();

    printf("\n Enter p, r, t");
    scanf("%d %d %d", &p, &r, &t);

    si = (p * r * t) / 100.0;

    printf("\n Simple Interest = %f", si);
    getch();
}
