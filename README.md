# 30-Percent-Discount
If the shopping amount is over 2000, it will be discount 30%



#include <iostream>
  
 using namespace std;
  
 int main()
 
  
 {
 	int money;
  
 	cout<<"please input the amount:\n";
  
 	cin>>money;
  
 	if (money>2000)    /*the amount is over 2,000 */
  
 	   money=money*7/10;    /*discount 30% */
  
 	   cout<<"The disciunted amount is"<<money<<endl;  /*disciunted amount */
 	
 	return 0;
  
 }
