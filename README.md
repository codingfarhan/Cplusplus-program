# C-program
This is a simple program to find number of vowels contained in the entered string.


#include<iostream.h>
#include<conio.h>
#include<stdio.h>
#include<string.h>

int main()
{
 int i, count=0;
 char str[99];
   
   cout<<"input a sentence/word/paragraph"<<endl;
   gets(str);
 
   int m=strlen(str);
 
 for(i=0; i<m; i++)
 {
     switch(str)
     {
         case'a': count++;
              break;
         case'e': count++;
              break;
          case'i': count++;
              break;
          case'o': count++;
              break;
          case'u': count++;
              break;
          case'A': count++;
              break;
         case'E': count++;
              break;
          case'I': count++;
              break;
          case'O': count++;
              break;
          case'U': count++;
              break;
          default: break;
     }
  }    
 
 getch();
 }
