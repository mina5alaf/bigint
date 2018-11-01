# bigint
#pragma once
#include <iostream>
#include <string>
#include <vector>
using namespace std;


class bigint
{
	vector <int>number;
	void add(bigint num, bigint athernum);
	void subtract(bigint num, bigint athernum);
	void add_int(int num);
	void subtract_int(int num);
public:
	char sign;
	string realnum;
	void setnumber(string x, char sign = '+', int maxsize = 50);
	void addnumbers(bigint num, bigint athernum);
	void Subtractnumbers(bigint num, bigint athernum);
	bool equal(bigint num);
	bool notequal(bigint num);
	bool graterthan(bigint num);
	bool smallerthan(bigint num);
	void addintnum(int num);
	void Subtractintnumbers(int num);
};


