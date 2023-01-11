#include<stdio.h>
int main()
{
    FILE *fp;
    fp=fopen("scaler.txt","r");
    if(!fp) 
    {
        printf("Error: File cannot be opened\n") ;
        return 0;
    }
    printf("Position pointer in the beginning : %ld\n",ftell(fp));
    char ch;
    while(fread(&ch,sizeof(ch),1,fp)==1)
    {
        printf("%c",ch);
    }
    printf("\nSize of file in bytes is : %ld\n",ftell(fp));
    fclose(fp);
    return 0;
} 
