# Test
testing repository to AG 45 school   
RUS++;                         
Изучайте с++!  

  
#include <iostream>//<<<это библиотеки(их очень мноого) этa дает вам потоки вывода и ввода (cout,cin)
using namespace std;//что-бы не писать все время std::cout std::cin

int main()   
{  
long a;    
    freopen("input.txt","r",stdin);    
    freopen("output.txt","w",stdout);  
    cin>>a;  
  cout << a<<'\n';  
  if (a%2==0)cout<<"Число четное";  
    else  
        cout<<"Число нечетное";  
}  
Программа считывает число из файла,выводит его и так же выводит четное ли оно.  
