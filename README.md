UPPER CASE to lower case:

#include <stdio.h>
#include<string.h>
int main()
{
   char str[100], us[100];
   int i= 0, j=0;
   printf("\n enter the string");
   fgets(str,100,stdin);
   for(i=0;str[i]!='\0';i++)
   {
       if(str[i]>='A' && str[i]<='Z')
       {
           str[i]=str[i]+32;
           }
   
      
   }
   printf("\n the converted string is :");
   printf("%s",str);
   
   
    return 0;
}
