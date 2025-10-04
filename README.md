# MILK-PRODUCTION
#include <iostream>
#include <iomanip>
using namespace std;

int main()
{
  float cost, profit, production;
  int cartons;
  cout<<"Enter te amount of milk produced in litres each morning: ";cin>>production;
  cartons = production/3.78;
  profit = cartons*0.27;
  cost = production*0.27;
  cout<<"The cartons needed to store the milk are "<<cartons<<endl;
  cout<<"The profit generated is "<<profit<<"$"<<endl;
  cout<<"The cost for producing milk "<<cost<<"$"<<endl;
  

    return 0;
}
