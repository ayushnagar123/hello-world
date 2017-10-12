// FLOYD'S TRINAGLE 
#include<conio.h>
#include<stdio.h>
int main()
{   int i,j,n;
    printf("\n Presenting The Floyd's Triangle ");
    printf("\n Enter a the magic no. - ");
    scanf("%d",&n);
    for(i=0;i<n;i++)
    {   for(j=0;j<n;j++)
        {   if(i>=j)
            {   if((i+j)%2==0)
                {   printf("1");
                }
                else
                {   printf("0");
                }
            }
            else
            {   printf(" ");
            }
        }
        printf("\n");

    }

    return 0;
}
