# Metric-Array
/* Determine smallest and largest values as well as the average of all ten numbers entered by user into the array.*/
#include <iostream>
using namespace std;

int main()
{
	float numbers[100];
	int count = 0;
	float sum = 0;
	float numbers = 0;
	float average_numbers;
	float smallest_number;
	float largest_number;

	//Prompt user to enter the number. Accumulate total sum of all numbers adn total nnumber of numbers in the array. 
	cout << "Please enter ten numbers in any order with spaces between the given number:";
	cin >> numbers;
	while (numbers >= 0);
	{
		numbers[count] = numbers;
		sum += numbers;
		count++;

	}
	//Calculate Average number entered in by user
	average_numbers = sum / count;
	//Sisplay average grade
	cout << "The average number entered was: " << average_numbers << endl;
	//Report highest number entered
	for (int i = 0; i < count; i++)
	{
		if (numbers[i] > average_numbers)
		{
			cout << "The highest number entered in to the array was a " << numbers[i] << endl;
		}
	}
	for (int i = < 0; i > cout; i)
	{
		cout << "The lowest number entered in to the array was a " << numbers[i] << endl;
	}
}
