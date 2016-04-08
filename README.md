# Dev-C
programas de c++
SUMAR LAS N POSICIONES DE UN VECTOR


#include <iostream> 
using namespace std; 
int main() 
{ 
int dimvec; 
int suma=0;
cout << "Ingresa la dimension del vector" << endl; 
cin >> dimvec; // Supongamos que ingrese 10 
int vector[dimvec]; // mi vector es de tamaño 10 
for(int i=0; i < dimvec ;i++)
 suma=suma+i;  
 cout << suma << " "; 
 return 1; 
} 
