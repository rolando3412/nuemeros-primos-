
#include <iostream>
#include <vector>
#include <conio.h>

using namespace std;
/* ejerccio #26  desarrollar un programa que dado un arreglo de orden n
 muestre en pantalla la suma de las pociciones con numeros primos
 programa en cpp*/

int main()
{
    int n = 0;
    int suma = 0;
    int numero[100];
   cout<<"digite el numero que tendra el arreglo  " << endl; 
   cin >>  n ; 

 // arreglo[]  guardando todos los elentos del vector
   for (int i = 0; i < n; i++) {
         cout << "digite el numero " << endl;
         cin >> numero[i]; 
   }
      // mostrando los elementos del vector con sus sus indices 

       for (int i = 0; i < n; i++) {
         cout<<"sub indice " << i  << "--> " <<numero[i] << endl; 

  }
     // suma de los numeros primos 
        for (int i = 0; i < n; i++) {
            if (numero[i] % 2 == 0) {
                suma = suma + numero[i];
            }
              // mostrando la suma de los numeros primos
        cout << "la suma de los numeros primos es " << suma << endl;

        }else
		 {            
		 cout << "el numero " << numero[i] << " no es primo" << endl; 


        }

    return 0;
}
