# Virtual-Base-Class-in-c-
//Virtual base class
#include<iostream>
using namespace std;
class A{
	
};
class B: virtual public A{
	
};
class C:virtual public A{
	
};
class baby:public B,public C{
	public:
		void set(){
			int a;
			cin>>a;
			cout<<"Your number is"<<a<<endl;
		}
};

int main(){
	baby L;
	L.set();
	return 0;
}
