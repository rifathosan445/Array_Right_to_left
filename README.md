# Array_Right_to_left



    #include<stdio.h>

    int main() {
    int a[5]={1,2,3,4,5},i,k;
    scanf("%d",&k);
    for(i=0;i<5;i++)
    {
           if(i+k<5)
              {
                  a[i]  = a[i+k];
              }
           else
           {

               a[i] =0;
           }



    }
    for(i=0;i<5;i++)
    {

           printf("%d,",a[i]);
    }
    return 0;
    }
