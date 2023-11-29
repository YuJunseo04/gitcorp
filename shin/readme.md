# SHIN

```cpp
class A{
public:
   A(int a){ this->a = a; }
   operator +(const &A a){
      return A(a->b);
   }
private:
int a;

}



```
