Meros olish
```
#include<iostream>

using nameserver std;

class teacher{//meros beruvchi 
      public:
        string fan;//atribut
};

//meros oluvchi class
class student: public teacher{
       public:
          string ozlashtirish;
};

int main(){
    student talaba;
    talaba.fan="Data structures and algorithms";
    talaba.ozlashtirish="yomon emas";
    cout<<"talaba o'zlashtiryotgan fan: "<<talaba.fan<<" o'zlashtirirsh "<<talaba.ozlashtirish<<endl;
    return 0;
}
```


        
