#include<iostream>
#include<cmath>
using namespace std;
int main()
{
	char x= '$';
	int a;
	cout << "Enter the number of tickers for A class seats:";
	cin >> a;
	int priceA = 15;
	cout << "Total cost for A class seats is:" << a * priceA <<x<< endl;

	int b;
	cout << "Enter the number of tickers for B class seats:";
	cin >> b;
	int priceB = 12;
	cout << "Total cost for B class seats is:" << b * priceB << x << endl;

	int c;
	cout << "Enter the number of tickers for C class seats:";
	cin >> c;
	int priceC = 9;
	cout << "Total cost for C class seats is:" << c * priceC << x << endl;
	return 0;

	cout << "Total income from all classes of seats is :" << (a * priceA) + (b * priceB) + (c * priceC) << x << endl;
}

