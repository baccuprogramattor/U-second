# U-second



Dichiarare un vettore di 10 elementi. Creare un ciclo for per il caricamento di 10 numeri interi nelle celle del vettore,
chiedendo l'input all'utente (Es. Inserisci l'elemento 1). Creare un secondo ciclo for che stampa tutti gli elementi del vettore(Es. L''elemento 1 è) .
*/
#include <iostream>
using namespace std;

int main()
{
	//dichiaro l'indice.
	int vettore[1];
	
	int i;
	for(i=0;i<=10;i++)
	{
		cin>>vettore[1];
		cout<<"Inserisci l\'elemento 1";
	}
for (i=0;i<=10;i++)
{
	cout<<"L\'elemento 1 e\'" <<vettore[i] <<endl;
}
		
	return 0;
}
