# cpp_classed
C++ tilida klasslar va ularni qo’llanilishi.

class yaratish:
```
class student{ // class nomi 
    public:   //atributlarning omaviyligini belgilash
      int age;  //atribut
      string name;  //atribut
};
```

obyekt olish:
```
#include<iostream>//qoshimcha

using namespace std;//nomlar fazosi

class student{
    public:
      int age;
      string name;
};

int main(){
    student talaba;//objekt
    
    talaba.name="BoburJon Obidov";//qiymat berish
    
    talaba.age=22;//***
    cout<<"Talaba "<<talaba.name<<" "<<talaba.age<<" yoshda"<<endl;
    return 0;
}
``` 
Obyektdan massiv qilib foydalanish:
```
#include<iostream>

using namespace std;

class student{
    public:
        string name;
        int age;
}

int main(){
    student talaba[2]; //array ko'rinishda e'lon qilish
    talaba[0].name="BoburJon Obidov";
    talaba[0].age=22;
    
    talaba[1].name="Fayzullo Mirobdullayev";
    talaba[1].age=19;
    
    cout<<"1 - talaba : "<<talaba[0].name<<", "<<talaba[0].age<<" yoshda\n";
    cout<<"2 - talaba : "<<talaba[1].name<<", "<<talaba[1].age<<" yoshda\n";
    return 0;
}
```

