#include <cs50.h>
#include <stdio.h>
#include <math.h>

int main(void)
{
    while (true)
    {
        float troco = get_float("Troco devido: ");
        int centavos = round(troco * 100);

        if (centavos > 0)
        {
            int moedas = 0;

            if (centavos >= 25)
            {
                troco = centavos / 25;
                moedas += troco;
                centavos = centavos - (troco * 25);
            }

            if (centavos >= 10)
            {
                troco = centavos / 10;
                moedas += troco;
                centavos = centavos - (troco * 10);
            }

            if (centavos >= 5)
            {
                troco = centavos / 5;
                moedas += troco;
                centavos = centavos - (troco * 5);
            }

            if (centavos >= 1)
            {
                troco = centavos / 1;
                moedas += troco;
                centavos = centavos - (troco * 1);
            }

            printf("%i moedas\n", moedas);

            break;
        }
    }
}
