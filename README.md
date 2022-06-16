# c++
Just For Learning
Operasi Input String Sebagai array of character
-------------------------------------------------
#include<iostream>
using namespace std;
main(){

 	char kalimat[100];
 	cout<<"Siapa Nama Kamu??  ";cin.getline(kalimat,100);
 	cout<<"Hallo	"<<kalimat<<"(~_~)\n";
 	cout<<"Kamu suka siapa	???";cin.getline(kalimat,100);
 	cout<<"hehe (-_-;) sebenarnya aku juga suka "<<kalimat<<" ,hehe;)";
}

  
 Hasil Program

Siapa Nama Kamu?? agum medisa;
Hallo  agum medisa(~_~);
Kamu suka siapa??? kamu;
hehe(-_-;) sebenarnya aku juga suka kamu, hehe;
