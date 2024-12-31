#include<iostream>
using namespace std;
int main(){
	double num1,num2;
	char op;
	
	cout<<"enter num1: ";
	cin>>num1;
	
	cout<<"enter num2: ";
	cin>>num2;
	
	cout<<"enter the operation(+,-,*,/): ";
	cin>>op;
	
	switch(op){
		case'+':
			cout<<num1<<op<<num2<<"="<<num1+num2<<endl;
			break;
	
	    case'-':
		    cout<<num1<<op<<num2<<"="<<num1-num2<<endl;
		break;
		
		case'*':
		    cout<<num1<<op<<num2<<"="<<num1*num2<<endl;
		break;
		
		case'/':
		    cout<<num1<<op<<num2<<"="<<num1/num2<<endl;
		break;
		
	}
	return 0;
} 
