-//programm #4 list_01.pdf

/*
type of gods:
	a,b,c:

type of customers:
	best, good, middle, bad





*/

#include <iostream>
#include <cmath>
#include <ctime>
#include <cmath>
#include <string>
using namespace std;

int main() {
	string tog, toc, tob;
	float prc, price, n, stavk, Vf;
	cout << "Enter type of gods (a, b, c): \t";
	getline(cin, tog);
	if (tog == "a") {
		cout << "Enter type of customers (best, good, middle, bad): \t";
		getline(cin, toc);
		if (toc == "best") {
			cout << "Enter type of bought (nal, chek, crdt): \t";
			getline(cin, tob);
			if (tob == "nal") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 0.6;
				price = price * prc;
				cout << "Incremental salary: \t" << price << " rubles" << endl;
			}
			
			else if (tob == "chek") {
				cout << "How much cost the god?: \t";
				cin >> price;
				cout << "How much transictions?: \t";
				cin >> n;
				cout << "How much %?(3 - 15): \t";
				cin >> stavk;
				Vf = price * (1 + (n * stavk) / 100);
				cout << "Incremental salary: \t" << Vf << " rubles" << endl;
			}
			else if (tob == "crdt") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 0.6;
				price = price * prc;
				cout << "How much transictions?: \t";
				cin >> n;
				cout << "How much %?(3 - 15): \t";
				cin >> stavk;
				Vf = price * pow((1 + stavk / 100), n);
				cout << "Incremental salary: \t" << Vf << " rubles" << endl;
			}
		}
		else if(toc == "good") {
			cout << "Enter type of bought (nal, chek, crdt): \t";
			getline(cin, tob);
			if (tob == "nal") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 0.7;
				price = price * prc;
				cout << "Incremental salary: \t" << price << " rubles" << endl;
			}

			else if (tob == "chek") {
				cout << "How much cost the god?: \t";
				cin >> price;
				cout << "How much transictions?: \t";
				cin >> n;
				cout << "How much %?(3 - 15): \t";
				cin >> stavk;
				Vf = price * (1 + (n * stavk) / 100);
				cout << "Incremental salary: \t" << Vf << " rubles" << endl;
			}
			else if (tob == "crdt") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 0.7;
				price = price * prc;
				cout << "How much transictions?: \t";
				cin >> n;
				cout << "How much %?(3 - 15): \t";
				cin >> stavk;
				Vf = price * pow((1 + stavk / 100), n);
				cout << "Incremental salary: \t" << Vf << " rubles" << endl;
			}
		}
		else if (toc == "middle") {
			cout << "Enter type of bought (nal, chek): \t";
			getline(cin, tob);
			if (tob == "nal") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 0.8;
				price = price * prc;
				cout << "Incremental salary: \t" << price << " rubles" << endl;
			}

			else if (tob == "chek") {
				cout << "How much cost the god?: \t";
				cin >> price;
				cout << "How much transictions?: \t";
				cin >> n;
				cout << "How much %?(3 - 15): \t";
				cin >> stavk;
				Vf = price * (1 + (n * stavk) / 100);
				cout << "Incremental salary: \t" << Vf << " rubles" << endl;
			}
		}
		else if (toc == "bad") {
			cout << "Enter type of bought (nal): \t";
			getline(cin, tob);
			if (tob == "nal") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 1;
				price = price * prc;
				cout << "Incremental salary: \t" << price << " rubles" << endl;
			}
		}
	}
	else if (tog == "b") {
		cout << "Enter type of customers (best, good, middle, bad): \t";
		getline(cin, toc);
		if (toc == "best") {
			cout << "Enter type of bought (nal, chek, crdt): \t";
			getline(cin, tob);
			if (tob == "nal") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 0.7;
				price = price * prc;
				cout << "Incremental salary: \t" << price << " rubles" << endl;
			}

			else if (tob == "chek") {
				cout << "How much cost the god?: \t";
				cin >> price;
				cout << "How much transictions?: \t";
				cin >> n;
				cout << "How much %?(3 - 15): \t";
				cin >> stavk;
				Vf = price * (1 + (n * stavk) / 100);
				cout << "Incremental salary: \t" << Vf << " rubles" << endl;
			}
			else if (tob == "crdt") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 0.7;
				price = price * prc;
				cout << "How much transictions?: \t";
				cin >> n;
				cout << "How much %?(3 - 15): \t";
				cin >> stavk;
				Vf = price * pow((1 + stavk / 100), n);
				cout << "Incremental salary: \t" << Vf << " rubles" << endl;
			}
		}
		else if (toc == "good") {
			cout << "Enter type of bought (nal, chek, crdt): \t";
			getline(cin, tob);
			if (tob == "nal") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 0.8;
				price = price * prc;
				cout << "Incremental salary: \t" << price << " rubles" << endl;
			}

			else if (tob == "chek") {
				cout << "How much cost the god?: \t";
				cin >> price;
				cout << "How much transictions?: \t";
				cin >> n;
				cout << "How much %?(3 - 15): \t";
				cin >> stavk;
				Vf = price * (1 + (n * stavk) / 100);
				cout << "Incremental salary: \t" << Vf << " rubles" << endl;
			}
			else if (tob == "crdt") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 0.8;
				price = price * prc;
				cout << "How much transictions?: \t";
				cin >> n;
				cout << "How much %?(3 - 15): \t";
				cin >> stavk;
				Vf = price * pow((1 + stavk / 100), n);
				cout << "Incremental salary: \t" << Vf << " rubles" << endl;
			}
		}
		else if (toc == "middle") {
			cout << "Enter type of bought (nal, chek): \t";
			getline(cin, tob);
			if (tob == "nal") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 0.9;
				price = price * prc;
				cout << "Incremental salary: \t" << price << " rubles" << endl;
			}

			else if (tob == "chek") {
				cout << "How much cost the god?: \t";
				cin >> price;
				cout << "How much transictions?: \t";
				cin >> n;
				cout << "How much %?(3 - 15): \t";
				cin >> stavk;
				Vf = price * (1 + (n * stavk) / 100);
				cout << "Incremental salary: \t" << Vf << " rubles" << endl;
			}
		}
		else if (toc == "bad") {
			cout << "Enter type of bought (nal): \t";
			getline(cin, tob);
			if (tob == "nal") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 1.05;
				price = price * prc;
				cout << "Incremental salary: \t" << price << " rubles" << endl;
			}
		}
	}
	else if (tog == "c") {
		cout << "Enter type of customers (best, good, middle, bad): \t";
		getline(cin, toc);
		if (toc == "best") {
			cout << "Enter type of bought (nal, chek, crdt): \t";
			getline(cin, tob);
			if (tob == "nal") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 0.8;
				price = price * prc;
				cout << "Incremental salary: \t" << price << " rubles" << endl;
			}

			else if (tob == "chek") {
				cout << "How much cost the god?: \t";
				cin >> price;
				cout << "How much transictions?: \t";
				cin >> n;
				cout << "How much %?(3 - 15): \t";
				cin >> stavk;
				Vf = price * (1 + (n * stavk) / 100);
				cout << "Incremental salary: \t" << Vf << " rubles" << endl;
			}
			else if (tob == "crdt") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 0.8;
				price = price * prc;
				cout << "How much transictions?: \t";
				cin >> n;
				cout << "How much %?(3 - 15): \t";
				cin >> stavk;
				Vf = price * pow((1 + stavk / 100), n);
				cout << "Incremental salary: \t" << Vf << " rubles" << endl;
			}
		}
		else if (toc == "good") {
			cout << "Enter type of bought (nal, chek, crdt): \t";
			getline(cin, tob);
			if (tob == "nal") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 0.9;
				price = price * prc;
				cout << "Incremental salary: \t" << price << " rubles" << endl;
			}

			else if (tob == "chek") {
				cout << "How much cost the god?: \t";
				cin >> price;
				cout << "How much transictions?: \t";
				cin >> n;
				cout << "How much %?(3 - 15): \t";
				cin >> stavk;
				Vf = price * (1 + (n * stavk) / 100);
				cout << "Incremental salary: \t" << Vf << " rubles" << endl;
			}
			else if (tob == "crdt") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 0.9;
				price = price * prc;
				cout << "How much transictions?: \t";
				cin >> n;
				cout << "How much %?(3 - 15): \t";
				cin >> stavk;
				Vf = price * pow((1 + stavk / 100), n);
				cout << "Incremental salary: \t" << Vf << " rubles" << endl;
			}
		}
		else if (toc == "middle") {
			cout << "Enter type of bought (nal, chek): \t";
			getline(cin, tob);
			if (tob == "nal") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 1;
				price = price * prc;
				cout << "Incremental salary: \t" << price << " rubles" << endl;
			}

			else if (tob == "chek") {
				cout << "How much cost the god?: \t";
				cin >> price;
				cout << "How much transictions?: \t";
				cin >> n;
				cout << "How much %?(3 - 15): \t";
				cin >> stavk;
				Vf = price * (1 + (n * stavk) / 100);
				cout << "Incremental salary: \t" << Vf << " rubles" << endl;
			}
		}
		else if (toc == "bad") {
			cout << "Enter type of bought (nal): \t";
			getline(cin, tob);
			if (tob == "nal") {
				cout << "How much cost the god?: \t";
				cin >> price;
				prc = 1.1;
				price = price * prc;
				cout << "Incremental salary: \t" << price << " rubles" << endl;
			}
		}
		}
	return 0;
}
