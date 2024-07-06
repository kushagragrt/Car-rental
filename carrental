#include<iostream>
#include<conio.h>
#include<stdlib.h>
using namespace std;
struct cars{
  string company[200]={"maruti","honda","toyoto","ford"};
  string model[200]={"swift","city","innova","figo"};
  string color[200]={"red","white","black","blue"};
  string maxspeed[200]={"180","200","210"};
  string fueltype[200]={"petrol","diesel","petrol","diesel"};
  string manufacturer[200]={"india","japan","india","india"};
  string price[200]={"500","600","700","800"};
  }car;

  void menu(){
	int num=1;
	for(int i=0;i<6;i++){
		cout<<"\t\t"<<num<<" "<<car.company[i]<<endl;
		num++;
	}
  }

void details(int choice){
	cout<<"\t\t--------------------------"<<endl;
	cout<<"\t\t company-----"<<car.company[choice-1]<<endl;
	cout<<"\t\t---------------------------"<<endl;
	cout<<"\t\t model------"<<car.model[choice-1]<<endl;
	cout<<"\t\t color-----"<<car.color[choice-1]<<endl;
	cout<<"\t\t mxspeed------"<<car.maxspeed[choice-1]<<endl;
	cout<<"\t\t fueltype-----"<<car.fueltype[choice-1]<<endl;
	cout<<"\t\t manufacturer-----"<<car.manufacturer[choice-1]<<endl;
	}


  int main(){
	// int login;
	// login();
  string decide="yes";
  cout<<"\t\t----------------------------------"<<endl;
  cout<<"\t\twelcome to car rental system"<<endl;
  cout<<"\t\t choose your option"<<endl;
  cout<<"\t\t----------------------------------"<<endl;

while(decide!="exit"){
	menu();
	cout<<"\t\t your choice:"<<endl;
	int choice;
	cin>>choice;
	//details
	details(choice);
	cout<<"\t\tAre you sure you want to rent this car?(yes/no/exit)"<<endl;
	cout<<"\t\t-----------------------"<<endl;
	cin>>decide;
	if(decide=="yes"||decide=="yes"){
		cout<<"\t\t car rented successfuly"<<endl;
		cout<<"\t\t--------------------------"<<endl;
		cout<<"\t\t company "<<car.company[choice]<<endl;
		cout<<"\t\t model "<<car.model[choice]<<endl;
		cout<<"\t\t color "<<car.color[choice]<<endl;
		cout<<"\t\t speed max "<<car.maxspeed[choice]<<endl;
        cout<<"\t\t fueltyp "<<car.fueltype[choice]<<endl;
		cout<<"\t\t price "<<car.price[choice]<<endl;
		cout<<"\t\t--------------------------"<<endl;
		cout<<"\t\tthankyou for visiting"<<endl;
		cout<<"\t\t--------------------------"<<endl;
		system("PAUSE");
		system("cls");

	}
	else if(decide=="no"||decide=="No"){
		cout<<"\t\tchoose your options"<<endl;
		cout<<"\t\t--------------------------"<<endl;
	}
  else if(decide=="exit"){
	cout<<"\t\tthankyou for using our system"<<endl;
	cout<<"\t\t--------------------------"<<endl;
	system("PAUSE");
	system("cls");
  }
  else{
	cout<<"\t\t invalid input"<<endl;
	cout<<"\t\t--------------------------"<<endl;
	system("PAUSE");
	system("cls");
  }
}
return 0;

  }
  int login(){
	string pass="";
	char ch;
	cout<<"\t\tcar rental sys login"<<endl;
	ch=_getch();
	while(ch!=13){
		pass.push_back(ch);
		cout<<'*';
		ch=_getch();
	}
	if(pass=="pass"){
		cout<<"\t password matched"<<endl;
		cout<<"\tloading "<<endl;
		system("PAUSE");
		cout<<"Access granted welcome toour system";
		system("cls");
	}
else{
	cout<<"\t password not matched";
	cout<<"\t try again"<<endl;
	system("PAUSE");
	system("cls");
	login();
}
  }
