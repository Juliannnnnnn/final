# final

this;

#include <iostream>
using namespace std;

int main() {

	int Type;
	cout <<"Enter the Type: 00 - Coffee, 11 - Tea, 22 - None" <<endl;
	cin >> Type;
	
	            if(Type == 00)
                { cout <<"Coffee: Ice is 3 dhs / Milk is 2 dhs / Black is 1 dh" <<endl;
                }
                  if(Type == 22 ) 
                { cout <<"None" <<endl; 
                }
                 else if (Type == 11)
                { cout <<"Tea: Ice is 3 dhs / Milk is 2 dhs / Black is 1 dh" << endl;
                                                     }
              
                
            cout << "Would you like sugar?(Y/N)" << endl;
	char input;
	cin >> input;
	
	switch (input) {
	    case 'Y':
	    case 'y': 
	        cout << "adding sugar..." << endl;
	            break;
	   case 'N':
	   case 'n':
	       cout << "no sugar requested..." << endl;
	       break;
	   default:
	       cout << "Invalid" << endl;  
	       
	}
     
     double money, amount, x;
	cout << "Enter the money: \n";
	cin >> money;
	cout << "Enter the amount: ";
	cin >> amount;
	x = amount - money; 
	if (x > 0) 
	{
		cout << "You have a money of: " << x << endl;
	}
	else if (x < 0) // For loss
	{
		cout << "Your change is:" << x << endl;
	}
	else if(x==0)
	{
		cout << "No loss no profit." << endl;
	}
	else
	{
		cout << "Incorrect input";

	}
	return 0;
}
                
