# switch-statements-C-
#include<iostream>
using namespace std;
int main() {
	char room; //variable tp hold user input 
	cout << " we are here the zoo!!" << endl;
	cout << " front (e)nerance, (f)ood stands 3: (l)ions 4: se(a)lions 5: lionf(i)sh 6: (p)enguins...." << endl;
	cin >> room; //get and store user input
	switch (room) {//start of the switch
	case 'e':
		cout << " lets go in side, come on!!" << endl;
		break; // this ;leaves the switch and not print anything else 
	case 'f':
		cout << " lets get something to eat im so hungry" << endl;
		break;
	case 'l':
		cout << " wow those lions so so cool with its big mane" << endl;
		break;
	case 'a':
		cout << " awwwww they are so cuteee" << endl;
		break;
	case 'i':
		cout << " those are some ugly fishh" << endl;
		break;
	case 'p':
		cout << " and these are the penguins they are the most popular" << endl;
		break;
	default://thia ia in a case the user types somethign dumb 
		cout << "sorry, that's not a room options." << endl;

	}
}
