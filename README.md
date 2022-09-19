# default-constructor
#include <iostream>
using namespace std;
class Cars
{
    string name;
    int price;
    public :
    Cars()
    {
         name = "hyaundai";
        price = 4000;
    }
    void display()
    {
        cout<<"car name is "<<name<<endl;
        cout<<"car price is "<<price;
    }
};
int main()
{
    Cars c1();
    c1.display();
}
