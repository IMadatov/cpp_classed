Metod yaratish:

```
#include<iostream>

using namespace std;

class student{
  public:
    void MyStipendya(){
        cout<<"Stependya 515";
    }
};

int main(){
    student talaba;
    talaba.MyStipendya();
    return 0;
 }
 ```
Tepada ichki metodga misol;

Tashqi matodga misol:
```
#include<iostream>

using namespace std;

class student{//class
    public:
      void MyStipendya();//
      
};
void student::MyStipendya(){
          cout<<"Stipendya \n";
}

int main(){
    student talaba;
    talaba.MyStipendya();
    return 0;
}
