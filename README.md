# Temperature-2
#Celsius to Fahrenheit conversion (simple code)
#include<iostream>
using namespace std;
int main()
{
	double fahren;   //declaring variable with datatype double
	double cels;     //declaring variable with datatype double

	cout << "Enter the temperature in Celsius: " << endl;
	cin >> cels;
	fahren = (cels * 9/5) + 32;   //formula to calculate temperature from celsius to fahrenheit
	cout << cels << " Celsius is " << fahren << " in Fahrenheit." << endl;
	return 0;
}
