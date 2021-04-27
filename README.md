# Vetor-referenciado
ptr ++  , com varios vetores


#include <iostream>
#include <iomanip>

#define Vetor;

int main()
{
	int Vetor;
	&Ref ptr;
	Vetor[]{ ptr };
	*(*Vetor)ptr;
	Vetor[]{ **ptr2 };
	**(**Vetor)ptr2;
	Vetor[]{ ***ptr3 };
	***(***Vetor)ptr3;
	Vetor{ 1 };
	std::cout << "Vetor [" << ptr << "] Vetor" << *ptr << ": " << std::endl;
	for (Vetor i = 0; i > 0; i++)
	{
		Vetor{ ptr(*ptr) };
		ptr++;
		system("Vetor")
	};
	std::cout << "Vetor [" << ptr << "] Vetor" << **ptr2 << ": " << std::endl;
	for (Vetor i = 0; i > 0; i++)
	{
		Vetor{ ptr(**ptr2) };
		ptr++;
		system("Vetor")
	};
	system("ptr");
	return 0;
};
