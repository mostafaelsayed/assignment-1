#include<iostream>
#include<string>
using namespace std;
class bank_account
{
public:
		bank_account();
		void print();
		void deposit(double b,double& f);
		void withdraw(double c,double& d);
private:
	string name;
	string number;
	double balance;
	};
	bank_account::bank_account()
	{
		balance=0;
	}
	void bank_account::print()
	{
		cout<<"please enter your name ";
		cin>>name;
		cout<<"please enter your code ";
		cin>>number;
		cout<<"please enter your balance ";
		cin>>balance;
		cout<<" name: "<<name;
		cout<<" code: "<<number;
		cout<<" balance: "<<balance ;
	}
	void bank_account::deposit(double b,double& f)
	{
		f=b+balance;
		cout<<"your new balance is"<<f;
	}
	void bank_account::withdraw(double c,double& d)
	{
		d=balance-c;
		cout<<"your new balance is"<<d;
	}
	int main()
	{
		bank_account mostafa;
		mostafa.print();
		cout<<"Do you want to deposit?yes or no";
		string ans1;
		cin>>ans1;
		if(ans1=="yes")
		{
			cout<<"please enter your required deposit amount";
		    double l,m;
		    cin>>l;
			mostafa.deposit(l,m);
		}
		else
		{
			cout<<"Do you want to withdraw?yes or no";
			cin>>ans1;
			if(ans1=="yes")
			{
				cout<<"please enter your required withdraw amount";
				double r,h;
				cin>>r;
		        mostafa.withdraw(r,h);
	
			}
			if(ans1=="no")
			{
				exit;
			}
		}
		
	}

	
		



			

			
		
