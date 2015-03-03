# 23
Here's the code


      #include <iostream>
      // Luis Angel Aguilar Carrillo A01225421
      using namespace std;
      
      int main(){
      
      	int nu[2];  // Crea un vector que almacena numeros enteros, y tiene una capacidad de 2 
      	int x, y;
      
      	cout << "Ingresa un numero" << endl;
      	cin >> x;
      
      	cout << "Ingresa otro numero" << endl;
      	cin >> y;
      
      	nu[0]= x*3;    // Guarda en la primera posición del vector la multiplicación de x*3
      
      	nu[1]= y*2;		// Guarda en la segunda posición del vector la multiplicación de y*2
      
      	cout << x << " * 3 = " << nu[0] << endl;		// muestra los valores
      	cout << y << " * 2 = " << nu[1] << endl;		// de los vectores
      
      	return 0;
      }
