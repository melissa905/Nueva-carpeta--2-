#include <iostream>
#include <conio.h>
#include <fstream>

using namespace std;

int main (){

string jueguitos="jueguitos.txt";
ofstream archivo;

archivo.open(jueguitos.c_str(),
Fstream::out);

archivo<<"si"
archivo<<"no";

archivo.close();
cout<<"Archivo creado correctamente";


return 0;

}