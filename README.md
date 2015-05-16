# C-Assignment1





#include <iostream>
using std::cin;
using std::cout;
using std::endl;

int main()
{
	int MICHAEL;
	
	cout << "Enter integer: ";
	cin >> MICHAEL;
	
	if (MICHAEL % 2 == 0)
	cout << "The integer is even: ";
	if (MICHAEL % 2 == 1)
	cout << "The integer is odd: ";
	
	return 0;
	system("PAUSE");
	return 'EXIT_SUCCESS';
}
