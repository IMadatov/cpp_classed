# cpp_classed
C++ tilida klasslar va ularni qo’llanilishi.

class yaratish:
```
class student{
    public:   //atributlarning omaviyligini belgilash
      int age;  //atribut
      string name;  //atribut
};
```

obyekt olish:
```
#include<iostream>

using namespace std;

class student{
    public:
      int age;
      string name;
};

int main(){
    student talaba;
    cout<<"Talaba ismini kiriting : ";
    cin>>talaba.name;
    cout<<"Talaba yoshini kiriting : ";
    cin>>talaba.age;
    
    cout<<"talaba "<<talaba.name<<" "<<talaba.age<<" yoshda"<<endl;
    return 0;
}
```

      
