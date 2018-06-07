/* escriba un programa que
 lea la nota final de cuatro alumnos y
  que calcule  la nota final media de los cuatro alumnos
*/

#include <iostream>

using namespace std;

int main(){
	
	float alumno1, alumno2, alumno3, alumno4, pp = 0, sp = 0, tp = 0, promedio = 0; //estos variables son los que se introduciran en la operacion
	
	cout<<"digite la calificacion del primer parcial:"; cin>>pp;  //se introducira la calificacion del primer 
	cout<<"digite la calificacion del segundo parcial:"; cin>>sp; //se introducira la segunda calificacion del segundo parcial
    cout<<"digite la calificacion del tercerparcial:"; cin>>tp;
	
	alumno1 = (pp+sp+tp) / 3; //este operacion es para sumar los tres parciales y dividirlo entre tres es la regla de tres para sacar el promedio
	
	cout<<"\nel promedio del primer alumno es:"<<alumno1<<endl;  //este codigo la funcion es para poder imprimir el promedio del alumno uno
	
	cout<<"digite la calificacion del primer parcial:"; cin>>pp;
	cout<<"digite la calificacion del segundo parcial:"; cin>>sp;
	cout<<"digite la calificacion del tercer parcial:"; cin>>tp;
	
	alumno2 = (pp+sp+tp) / 3;
	cout<<"\nel promedio del segundo alumno es:"<<alumno2<<endl; //este operacion es para la calificacion del segundo alumno 
	
	cout<<"digite la calificacion del primer parcial:"; cin>>pp;
	cout<<"digite la calificacion del segundo parcial:"; cin>>sp;
	cout<<"digite la calificacion del tercer parcial:"; cin>>tp;
	
	alumno3 = (pp+sp+tp) / 3;
	
	cout<<"\nel promedio del tercer alumno es:"<<alumno3<<endl;
	
	cout<<"digite la calificacion del primer parcial:"; cin>>pp;
	cout<<"digite la calificacion del segundo parcial:"; cin>>sp;
	cout<<"digite la calificacion del tercer parcial:"; cin>>tp;
	
	alumno4 = (pp+sp+tp) / 3;
	cout<<"\nel promedio del cuarto alumno es:"<<alumno4<<endl;
	
	
	return 0;
}
