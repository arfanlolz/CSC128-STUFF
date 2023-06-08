#include <iostream>
#include <iomanip>
#include <windows.h>
#include <stdlib.h>
using namespace std;
int main()
{
	system("Color 96");
    // Declare variables for food option and quantity.
    char meal, beverage, temp;
    
    int quantityA, quantityB, quantityC, 
	quantityD, quantityE, quantityF, 
	quantityG, quantityH, quantityI, 
	quantityJ, quantityK, quantityL, 
	quantityM, quantityN, quantityO, 
	quantityP, quantityQ, quantityR, 
	quantityS, quantityT, quantityU,
	quantityV, quantityW, quantityX;
	
	int i = 0;
	int j = 0;
	int k = 0;
	int l = 0;
	int m = 0;
	int n = 0;
	int o = 0;
	int p = 0;
	
	
	
	double ayam_penyet = 9.00, ayam_bakar = 9.00, 
	ayam_geprek = 10.00, ngoreng_biasa = 9.00, 
	ngoreng_ayam = 10.00, ngoreng_seafood = 11.00, 
	ngoreng_daging = 14.00, mi_kari = 10.00, 
	mi_jawa = 10.00, mgoreng_biasa = 10.00, 
	mgoreng_ayam = 10.00, mgoreng_mamak = 10.00,
    mgoreng_seafood = 11.00, mgoreng_daging = 14.00,
    miloP = 2.50, miloS = 3.00, miloOP = 2.00,
    miloOS = 2.50, kopiP = 2.00, kopiS = 2.50,
    kopiOP = 1.50, kopiOS = 2.00, tehP = 2.00,
    tehS = 2.50, tehOP = 1.50, tehOS = 2.00,
    tehTP = 3.00, tehTS = 3.50, soda = 2.00,
    airmineral = 1.50, airminuman = 1.00;
    
    string username, location;
    
    
    // Display Menu to user.
    char greetingTitle[30] = "Welcome to Kedai Pak Abu";
    
    cout << setw(45) << right << " ";
    
    while(i < 30){
    	cout << greetingTitle[i];
    	Sleep(30);
    	i++;
	}
	
	cout << endl;
	
	while(j < 120){
		cout << "-";
		j++;
	}
	
	cout << " " << endl;
	
	cout << "NASI:" << setw(69) << right << "MILO/KOPI/TEH:" << endl;
    cout << setw(30) << left << "A)Nasi Ayam Penyet" << setw(30) << left << "9.00" << setw(30) << left << "O)Milo" << "2.50(P)" << setw(10) << right << "3.00(S)" << endl;
    cout << setw(30) << left << "B)Nasi Ayam Bakar" << setw(30) << left << "9.00" << setw(30) << left << "P)Milo O" << "2.00(P)" << setw(10) << right << "2.50(S)" << endl;
    cout << setw(30) << left << "C)Nasi Ayam Geprek" << setw(30) << left << "10.00" << setw(30) << left << "Q)Kopi" << "2.00(P)" << setw (10) << right << "2.50(S)" << endl;
    cout << setw(30) << left << "D)Nasi Goreng Biasa" << setw(30) << left << "9.00" << setw(30) << left << "R)Kopi O" << "1.50(P)" << setw(10) << right << "2.00(S)" << endl;
    cout << setw(30) << left << "E)Nasi Goreng Ayam" << setw(30) << left << "10.00" << setw(30) << left << "S)Teh" << "2.00(P)" << setw(10) << right << "2.50(S)" << endl;
    cout << setw(30) << left << "F)Nasi Goreng Seafood" << setw(30) << left << "11.00" << setw(30) << left << "T)Teh 0" << "1.50(P)" << setw(10) << right << "2.00(S)" << endl;
    cout << setw(30) << left << "G)Nasi Goreng Daging" << setw(30) << left << "14.00" << setw(30) << left << "U)Teh Tarik" << "3.00(P)" << setw(10) << right << "3.50(S)" << endl;
    cout << endl;
    cout << setw(60) << left << "MI:" << setw(60) << left << "AIR TIN/LAIN-LAIN:" << endl;
    cout << setw(30) << left << "H)Mi Kari" << setw(30) << left << "10.00" << setw(30) << left << "V)Cola/Sprite/Pepsi/A&W" << "2.00" << endl;
    cout << setw(30) << left << "I)Mi Jawa" << setw(30) << left << "10.00" << setw(30) << left << "W)Air Minuman" << "1.00" << endl;
    cout << setw(30) << left << "J)Mi Goreng Biasa" << setw(30) << left << "10.00" << setw(30) << left << "X)Air Mineral" << "1.50" << endl;
    cout << setw(30) << left << "K)Mi Goreng Ayam" << setw(30) << left << "10.00" << endl;
    cout << setw(30) << left << "L)Mi Goreng Mamak" << setw(30) << left << "10.00"  << endl;
    cout << setw(30) << left << "M)Mi Goreng Seafood" << setw(30) << left << "11.00" << endl;
    cout << setw(30) << left << "N)Mi Goreng Daging" << setw(30) << left << "14.00" << endl;
	
	
	while(k < 119){
		cout << "-";
		k++;
	}
	
	cout << " " << endl;
	

	// Ask for input from user:
	char getinputMeal[15] = "Choose meal: ";
	char getinputBeverage[18] = "Choose Beverage: ";
	
	while(l < 15){
		cout << getinputMeal[l];
		Sleep(50);
		l++;
	}
	
	cin >> meal;
	
	char quanttofmeal[11] = "Quantity: ";
	char quanttofBeverage[11] = "Quantity: ";
	char askHotCold[27] = "Choose Hot(P) or Cold(S): ";
	if (meal == 'A' || meal == 'a' ){
		while (n < 11){
			cout << quanttofmeal[n];
			Sleep(50);
			n++;
		}
		
    	cin >> quantityA;
    	
		while(m < 18 ){
			cout << getinputBeverage[m];
			Sleep(50);
			m++;
		}
		
		cin >> beverage;
		
			if (beverage == 'O' || beverage == 'o' ){
				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityO;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;		
			}
    		else if (beverage == 'P' || beverage == 'p'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityP;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'Q' || beverage == 'q'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityQ;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'R' || beverage == 'r'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityR;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'S' || beverage == 's'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityS;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'T' || beverage == 't'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityT;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
			else if (beverage == 'U' || 'u'){ 
			  while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityU;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			 else if (beverage == 'V' || beverage == 'v'){
   			 	while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityV;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			else if (beverage == 'W' || beverage == 'w'){
   				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityW;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'X' || beverage == 'x'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityX;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
    		}
			else {
				cout << "Item not found" << endl;
			}
	}
    else if (meal == 'B' || meal == 'b'){
    		while (n < 11){
			cout << quanttofmeal[n];
			Sleep(50);
			n++;
		}
		
    	cin >> quantityB;
    	
		while(m < 18 ){
			cout << getinputBeverage[m];
			Sleep(50);
			m++;
		}
		
		cin >> beverage;
		
			if (beverage == 'O' || beverage == 'o' ){
				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityO;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;		
			}
    		else if (beverage == 'P' || beverage == 'p'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityP;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'Q' || beverage == 'q'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityQ;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'R' || beverage == 'r'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityR;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'S' || beverage == 's'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityS;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'T' || beverage == 't'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityT;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
			else if (beverage == 'U' || 'u'){ 
			  while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityU;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			 else if (beverage == 'V' || beverage == 'v'){
   			 	while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityV;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			else if (beverage == 'W' || beverage == 'w'){
   				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityW;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'X' || beverage == 'x'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityX;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
    		}
			else {
				cout << "Item not found" << endl;
			}
	}
    else if (meal == 'C' || 'c'){
    			while (n < 11){
			cout << quanttofmeal[n];
			Sleep(50);
			n++;
		}
		
    	cin >> quantityC;
    	
		while(m < 18 ){
			cout << getinputBeverage[m];
			Sleep(50);
			m++;
		}
		
		cin >> beverage;
		
			if (beverage == 'O' || beverage == 'o' ){
				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityO;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;		
			}
    		else if (beverage == 'P' || beverage == 'p'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityP;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'Q' || beverage == 'q'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityQ;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'R' || beverage == 'r'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityR;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'S' || beverage == 's'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityS;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'T' || beverage == 't'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityT;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
			else if (beverage == 'U' || 'u'){ 
			  while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityU;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			 else if (beverage == 'V' || beverage == 'v'){
   			 	while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityV;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			else if (beverage == 'W' || beverage == 'w'){
   				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityW;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'X' || beverage == 'x'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityX;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
    		}
			else {
				cout << "Item not found" << endl;
			}
	}
    else if (meal == 'D' || 'd'){
    		while (n < 11){
			cout << quanttofmeal[n];
			Sleep(50);
			n++;
		}
		
    	cin >> quantityD;
    	
		while(m < 18 ){
			cout << getinputBeverage[m];
			Sleep(50);
			m++;
		}
		
		cin >> beverage;
		
			if (beverage == 'O' || beverage == 'o' ){
				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityO;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;		
			}
    		else if (beverage == 'P' || beverage == 'p'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityP;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'Q' || beverage == 'q'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityQ;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'R' || beverage == 'r'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityR;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'S' || beverage == 's'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityS;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'T' || beverage == 't'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityT;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
			else if (beverage == 'U' || 'u'){ 
			  while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityU;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			 else if (beverage == 'V' || beverage == 'v'){
   			 	while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityV;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			else if (beverage == 'W' || beverage == 'w'){
   				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityW;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'X' || beverage == 'x'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityX;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
    		}
			else {
				cout << "Item not found" << endl;
			}
	}
    else if (meal == 'E' || 'e'){
    		while (n < 11){
			cout << quanttofmeal[n];
			Sleep(50);
			n++;
		}
		
    	cin >> quantityE;
    	
		while(m < 18 ){
			cout << getinputBeverage[m];
			Sleep(50);
			m++;
		}
		
		cin >> beverage;
		
			if (beverage == 'O' || beverage == 'o' ){
				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityO;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;		
			}
    		else if (beverage == 'P' || beverage == 'p'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityP;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'Q' || beverage == 'q'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityQ;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'R' || beverage == 'r'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityR;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'S' || beverage == 's'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityS;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'T' || beverage == 't'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityT;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
			else if (beverage == 'U' || 'u'){ 
			  while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityU;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			 else if (beverage == 'V' || beverage == 'v'){
   			 	while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityV;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			else if (beverage == 'W' || beverage == 'w'){
   				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityW;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'X' || beverage == 'x'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityX;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
    		}
			else {
				cout << "Item not found" << endl;
			}
	}
    else if (meal == 'F' || 'f'){
    		while (n < 11){
			cout << quanttofmeal[n];
			Sleep(50);
			n++;
		}
		
    	cin >> quantityF;
    	
		while(m < 18 ){
			cout << getinputBeverage[m];
			Sleep(50);
			m++;
		}
		
		cin >> beverage;
		
			if (beverage == 'O' || beverage == 'o' ){
				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityO;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;		
			}
    		else if (beverage == 'P' || beverage == 'p'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityP;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'Q' || beverage == 'q'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityQ;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'R' || beverage == 'r'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityR;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'S' || beverage == 's'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityS;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'T' || beverage == 't'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityT;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
			else if (beverage == 'U' || 'u'){ 
			  while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityU;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			 else if (beverage == 'V' || beverage == 'v'){
   			 	while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityV;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			else if (beverage == 'W' || beverage == 'w'){
   				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityW;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'X' || beverage == 'x'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityX;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
    		}
			else {
				cout << "Item not found" << endl;
			}
	}
	else if (meal == 'G' || 'g'){
    		while (n < 11){
			cout << quanttofmeal[n];
			Sleep(50);
			n++;
		}
		
    	cin >> quantityG;
    	
		while(m < 18 ){
			cout << getinputBeverage[m];
			Sleep(50);
			m++;
		}
		
		cin >> beverage;
		
			if (beverage == 'O' || beverage == 'o' ){
				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityO;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;		
			}
    		else if (beverage == 'P' || beverage == 'p'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityP;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'Q' || beverage == 'q'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityQ;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'R' || beverage == 'r'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityR;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'S' || beverage == 's'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityS;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'T' || beverage == 't'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityT;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
			else if (beverage == 'U' || 'u'){ 
			  while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityU;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			 else if (beverage == 'V' || beverage == 'v'){
   			 	while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityV;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			else if (beverage == 'W' || beverage == 'w'){
   				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityW;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'X' || beverage == 'x'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityX;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
    		}
			else {
				cout << "Item not found" << endl;
			}
	}
    else if (meal == 'H' || 'h'){
    		while (n < 11){
			cout << quanttofmeal[n];
			Sleep(50);
			n++;
		}
		
    	cin >> quantityH;
    	
		while(m < 18 ){
			cout << getinputBeverage[m];
			Sleep(50);
			m++;
		}
		
		cin >> beverage;
		
			if (beverage == 'O' || beverage == 'o' ){
				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityO;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;		
			}
    		else if (beverage == 'P' || beverage == 'p'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityP;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'Q' || beverage == 'q'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityQ;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'R' || beverage == 'r'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityR;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'S' || beverage == 's'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityS;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'T' || beverage == 't'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityT;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
			else if (beverage == 'U' || 'u'){ 
			  while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityU;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			 else if (beverage == 'V' || beverage == 'v'){
   			 	while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityV;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			else if (beverage == 'W' || beverage == 'w'){
   				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityW;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'X' || beverage == 'x'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityX;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
    		}
			else {
				cout << "Item not found" << endl;
			}
	}
    else if (meal == 'I' || 'i'){
    		while (n < 11){
			cout << quanttofmeal[n];
			Sleep(50);
			n++;
		}
		
    	cin >> quantityI;
    	
		while(m < 18){
			cout << getinputBeverage[m];
			Sleep(50);
			m++;
		}
		
		cin >> beverage;
		
			if (beverage == 'O' || beverage == 'o' ){
				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityO;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;		
			}
    		else if (beverage == 'P' || beverage == 'p'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityP;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'Q' || beverage == 'q'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityQ;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'R' || beverage == 'r'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityR;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'S' || beverage == 's'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityS;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'T' || beverage == 't'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityT;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
			else if (beverage == 'U' || 'u'){ 
			  while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityU;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			 else if (beverage == 'V' || beverage == 'v'){
   			 	while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityV;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			else if (beverage == 'W' || beverage == 'w'){
   				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityW;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'X' || beverage == 'x'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityX;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
    		}
			else {
				cout << "Item not found" << endl;
			}
	}
    else if (meal == 'J' || 'j'){
    		while (n < 11){
			cout << quanttofmeal[n];
			Sleep(50);
			n++;
		}
		
    	cin >> quantityJ;
    	
		while(m < 18 ){
			cout << getinputBeverage[m];
			Sleep(50);
			m++;
		}
		
		cin >> beverage;
		
			if (beverage == 'O' || beverage == 'o' ){
				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityO;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;		
			}
    		else if (beverage == 'P' || beverage == 'p'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityP;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'Q' || beverage == 'q'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityQ;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'R' || beverage == 'r'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityR;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'S' || beverage == 's'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityS;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'T' || beverage == 't'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityT;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
			else if (beverage == 'U' || 'u'){ 
			  while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityU;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			 else if (beverage == 'V' || beverage == 'v'){
   			 	while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityV;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			else if (beverage == 'W' || beverage == 'w'){
   				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityW;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'X' || beverage == 'x'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityX;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
    		}
			else {
				cout << "Item not found" << endl;
			}
	}
    else if (meal == 'K' || 'k'){
    		while (n < 11){
			cout << quanttofmeal[n];
			Sleep(50);
			n++;
		}
		
    	cin >> quantityK;
    	
		while(m < 18 ){
			cout << getinputBeverage[m];
			Sleep(50);
			m++;
		}
		
		cin >> beverage;
		
		if (beverage == 'O' || beverage == 'o' ){
				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityO;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;		
			}
    		else if (beverage == 'P' || beverage == 'p'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityP;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'Q' || beverage == 'q'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityQ;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'R' || beverage == 'r'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityR;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'S' || beverage == 's'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityS;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'T' || beverage == 't'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityT;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
			else if (beverage == 'U' || 'u'){ 
			  while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityU;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			 else if (beverage == 'V' || beverage == 'v'){
   			 	while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityV;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			else if (beverage == 'W' || beverage == 'w'){
   				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityW;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'X' || beverage == 'x'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityX;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
    		}
			else {
				cout << "Item not found" << endl;
			}
	}
    else if (meal == 'L' || 'l'){
    		while (n < 11){
			cout << quanttofmeal[n];
			Sleep(50);
			n++;
		}
		
    	cin >> quantityL;
    	
		while(m < 18 ){
			cout << getinputBeverage[m];
			Sleep(50);
			m++;
		}
		
		cin >> beverage;
		
			if (beverage == 'O' || beverage == 'o' ){
				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityO;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;		
			}
    		else if (beverage == 'P' || beverage == 'p'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityP;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'Q' || beverage == 'q'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityQ;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'R' || beverage == 'r'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityR;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'S' || beverage == 's'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityS;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'T' || beverage == 't'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityT;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
			else if (beverage == 'U' || 'u'){ 
			  while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityU;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			 else if (beverage == 'V' || beverage == 'v'){
   			 	while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityV;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			else if (beverage == 'W' || beverage == 'w'){
   				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityW;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'X' || beverage == 'x'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityX;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
    		}
			else {
				cout << "Item not found" << endl;
			}
	}
	else if (meal == 'M' || 'm'){
      		while (n < 11){
			cout << quanttofmeal[n];
			Sleep(50);
			n++;
		}
		
    	cin >> quantityM;
    	
		while(m < 18 ){
			cout << getinputBeverage[m];
			Sleep(50);
			m++;
		}
		
		cin >> beverage;
		
			if (beverage == 'O' || beverage == 'o' ){
				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityO;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;		
			}
    		else if (beverage == 'P' || beverage == 'p'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityP;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'Q' || beverage == 'q'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityQ;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'R' || beverage == 'r'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityR;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'S' || beverage == 's'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityS;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'T' || beverage == 't'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityT;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
			else if (beverage == 'U' || 'u'){ 
			  while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityU;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			 else if (beverage == 'V' || beverage == 'v'){
   			 	while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityV;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			else if (beverage == 'W' || beverage == 'w'){
   				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityW;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'X' || beverage == 'x'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityX;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
    		}
			else {
				cout << "Item not found" << endl;
			}
	}
	else if (meal == 'N' || 'n'){
			while (n < 11){
			cout << quanttofmeal[n];
			Sleep(50);
			n++;
		}
		
    	cin >> quantityN;
    	
		while(m < 18){
			cout << getinputBeverage[m];
			Sleep(50);
			m++;
		}
		
		cin >> beverage;
		
			if (beverage == 'O' || beverage == 'o' ){
				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityO;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;		
			}
    		else if (beverage == 'P' || beverage == 'p'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityP;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'Q' || beverage == 'q'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityQ;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'R' || beverage == 'r'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityR;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'S' || beverage == 's'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityS;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'T' || beverage == 't'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityT;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
			else if (beverage == 'U' || 'u'){ 
			  while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityU;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			 else if (beverage == 'V' || beverage == 'v'){
   			 	while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityV;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
   			else if (beverage == 'W' || beverage == 'w'){
   				while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityW;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
			}
    		else if (beverage == 'X' || beverage == 'x'){
    			while (o < 11){
					cout << quanttofBeverage[o];
    				Sleep(50);
    				o++;
				}
    			
    			cin >> quantityX;

    			
    			while (p < 27){
    				cout << askHotCold[p];
    				Sleep(50);
    				p++;
    			}
    			
    			cin >> temp;
    			cout << " " << endl;
    		}
			else {
				cout << "Item not found" << endl;
			}
	}
	else {
		cout << "Item not found" << endl;
	}
	
	return 0;
	
}
