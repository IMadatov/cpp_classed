**Palimarifizm**
```
#include <iostream>

using namespace std;

//Asosiy class
class Teacher {
  public:
    void fan() {
      cout << "Data Structura and Algorithm\n";
    }
};

//meros class
class student1 : public Teacher {
  public:
    void fan() {
      cout << "Elektronika \n";
    }
};

//meros class
class student2 : public Teacher {
  public:
    void fan() {
      cout << "Diskret \n";
    }
};

int main() {
  //object
  student1 talaba1;
  student2 talaba2;
  Teacher ustoz;
  
  //metodni chaqirish
  talaba1.fan();
  talaba2.fan();
  ustoz.fan();
  
  return 0;
}

```
