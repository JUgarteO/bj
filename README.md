# mesasbj
Código Lenguaje C, esto se debe transformar a html

...test

//Copyright (C) {$2019} - Ing. Jorge Ugarte Olguín
// Creación base datos y determinar cantidad mesas
// Date of creation: Dec 7, 2019

//10 mesas; 6 sillas c/mesa

xdel(winsid());
clear;
clc;

disp('REGISTRO BJ');
jugador=struct('nombre',' ','apellido',' ','rut',' ');
n=input('Ingrese numero de jugadores: ');
m=input('Ingrese el numero de mesas: ');
a=60;   //cantidad total de asientos
for i=1:n
    printf('Jugador #%d\n',i); 
    jugador(i).nombre=input('Ingrese nombre: ','s');
    jugador(i).apellido=input('Ingrese apellido: ','s');
    jugador(i).rut=input('Ingrese RUT (sin puntos ni digito verificador): ');
end
disp('LISTADO DE JUGADORES  REGISTRADOS EN EL TORNEO');
printf('Nombre\tApellido\tRut\n' );
for i=1:n
    nombre=jugador(i).nombre;
    apellido=jugador(i).apellido;
    rut=jugador(i).rut;
    printf('%s\t%s\t%d\n',nombre,apellido,rut);

num.mesas=ceil(n/6); //num.mesas=jugadores(n)/asientos(a), aproximados<
//x=num.mesas;
//disp(x)
y=ceil(n/m);
//printf('La cantidad de participantes por mesa es de: %s, (n/6) %d);

end
