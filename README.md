# include <stdio.h>   
int main()   
{   
 int r ;   
  char n[20],s[20],s1,i[20];
 printf(" Enter any name: ") ;   
 gets(n) ;   
printf(" Enter any stream: ") ;   
 gets(s);
printf(" Enter a section: ") ;   
 scanf("%c",&s1) ;
printf(" Enter a roll: ") ;   
scanf("%d", &r) ;
printf(" Enter institute name: ") ;   
scanf("%s",i);
printf("\nName : %s\n",n);
printf("Stream:%s\n",s);
printf("Section:%c\n",s1);
printf("Roll number:%d\n",r);
printf("Institute:%s\n",i);
return 0 ;   
}
