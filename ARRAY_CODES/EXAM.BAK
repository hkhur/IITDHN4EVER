#include<fstream.h>
#include<stdio.h>
#include<conio.h>
#include<stdlib.h>
void main()
{
clrscr();
ifstream fin("fuddu.txt",ios::in);
ofstream fout("fuddu1.txt",ios::out);
char ch;
fin.get(ch);
while(!fin.eof())
{
fout.put(ch);
fout.put('#');
fin.get(ch);
if(ch=='\n')
break;
}
cout<<" ALL DONE : ";
fin.close();
fout.close();
getch();
}