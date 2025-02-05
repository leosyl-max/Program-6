#include<stdio.h>
#include<string.h>
int main() {
       char name1[10]="sriram ";
       char abc[10];
       char name2[10]="sriraam";
       strcpy(abc, name1);
       printf("%s", abc);
       strcat(name1, name2);
       printf("%s",name1);
       printf("%d\n", strcmp(name1, name2));
       return 0;
       }
