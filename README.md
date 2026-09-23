Oop Unit 1 Assignment 1 

#include<iostream>
using namespace std;

class books
{
public:
   int price;
   int numberofpages;
   string authorname;
   string titlename;

   void librarybooks()
   {
      cout << "Price: " << price << endl;
      cout << "NumberOfPages: " << numberofpages << endl;
      cout << "AuthorName: " << authorname << endl;
      cout << "Titlename: " << titlename << endl;
   }
};

int main()
{
   books b1;

   b1.price = 750;
   b1.numberofpages = 350;
   b1.authorname = "R.K.Sharma";
   b1.titlename = "C++Programming";

   b1.librarybooks();

   return 0;
}

output
Price: 750
NumberOfPages: 350
AuthorName: R.K.Sharma
Titlename: C++Programming