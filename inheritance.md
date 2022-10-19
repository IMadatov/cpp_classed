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

**Bir classdan bir necha meros olish**

```
#include<iostream>

using nameserver std;

class teacher{//meros beruvchi 
      public:
        string fan;//atribut
};

//meros olish
class student1: public teacher{
       public:
          string ozlashtirish;
};
//merosdan meros olish
class student2: public student1{
       public:
          shor int baho;
};

int main(){
    student2 talaba2;
    talaba2.fan="Data structures and algorithms";
    talaba2.ozlashtirish="yomon emas";
    talaba2.baho
    
    cout<<"talaba o'zlashtiryotgan fan: "<<talaba2.fan<<" o'zlashtirirsh "<<talaba2.ozlashtirish<<", baho "<<talaba2.baho<<endl;
    return 0;
}
```

**Bir nechata classlardan meros olish**
```
#include<iostream>

using nameserver std;

class teacher1{//meros beruvchi 
      public:
        string fan1="Data Strucktura"
};
class teacher2{
      puclic:
            string fan2="diskret";
};
class student:public teacher1,public teacher2{
      public:
            int GPA=4;
};


int main(){
    student talaba;
    cout<<" Fan1 "<<talaba.fan1<<", Fan2 "<<talaba.fan2<<", GPA = "<<talaba.GPA<<endl;    
    return 0;
}
```


        
