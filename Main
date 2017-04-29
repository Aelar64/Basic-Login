#include "stdafx.h"
#include <iostream>
#include <string>

using namespace std;

int main()
{
	string username;
	string password;

	bool userSuccess = false;

	cout << "Names and Passwords are key-sensitive!\n\n";

	cout << "Username: ";
	cin >> username;
	cout << "\n\n";
	cout << "Password: ";
	cin >> password;
	cout << "\n\n";

	if(username == "Name" && password == "Pass")
	{
		cout << "Correct login. Welcome, " << username << "." << endl << endl;
		userSuccess = true;
		system("pause");
	}
	else {
		cout << "Incorrect credidentials. Please try again another time.\n\n";
		system("pause");
	}while (userSuccess == false)
    return 0;
}

