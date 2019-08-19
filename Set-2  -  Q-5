#include <iostream>
#include "Sequence.h"
using namespace std;
class Sequence
{
	int n, array[256];
public:
	void receive();
	void retrieve();

};
void Sequence::receive()
{
	cout << "Enter number of elements to be in the sequence" << endl;
	cin >> n;
	for (int i = 0; i < n; i++)
	{
		cin >> array[i];
	}
	cout << endl;
}
void Sequence::retrieve()
{
	cout << "Inversion count is given by: "<<endl;
	for (int i = 0; i < n; i++)
	{
		int count = 0;
		for (int j = 0; j < n; j++)
		{
			if(i< j && array[i] < array[j])
				count++;
		}
		
		cout << count << " ";
	}
	cout << endl;
}
int main()
{
	Sequence sequence;
	sequence.receive();
	sequence.retrieve();

	return 0;
}
