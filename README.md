#c language 
#include<stdio.h>
int main (void)
{
    int day, dmoney , tmoney , dexp , texp, profit ;
     tmoney =0; 
     texp =0; 
    for ( day = 1; day <= 31; day++)
    {
        printf("%d day money is ",day);
        scanf("%d",&dmoney);
        printf("%d day exp is ",day );
        scanf("%d",&dexp);

        tmoney = tmoney + dmoney;
        texp = texp + dexp;
    }

    printf("\n");
    printf("\n");
    printf("\n");

    
    profit = tmoney - texp ;
    printf("total money is %d \n",tmoney);
    printf("total exp is %d  \n",texp);
   int loss;
   if (profit <= 0)
   {
       printf("u have loss in this month \n");
       printf("the loss is %d ",profit);
   }
   else
   {
       printf("The profit is %d ",profit);
   }
   int close;
    scanf("%d",&close);
    return 0;
      
}
