# asimplecalculator
Here is a simple calculator code. Gotta start small right? 

#include <iostream>
#include <cmath>

using namespace std;

int main(){
rerun:

cout<<"*****************************"<<endl;
cout<<"* Welcome to my Calculator! *"<<endl;
cout<<"*****************************"<<endl;

int a;
int b;
char op;


cout<<"Enter your problem! ;) \n";
cout<<"First number : ";
cin>>a;

cout<<"Enter what operator you'd like to use"<<endl;
cout<<"Type (+, -, /, *) : ";
cin>>op;

cout<<"Second number : ";
cin>>b;

int sum;

if(op == '+'){
    sum = a + b;
}else if(op == '-'){
    sum = a - b;
}else if(op == '*'){
    sum = a * b;
}else if(op == '/'){
    sum = a / b;
}else{
    cout<<"HEY! Invalid input! "<<endl;
}
cout<<"The answer to your problem is "<<sum<<endl;
cout<<" "<<endl;


cout<<"Have another problem? (y/n) "<<endl;

string yorn;
cin>>yorn;

if(yorn == "y" || yorn == "Y")
    goto rerun;
else

cout<<"********************"<<endl;
cout<<"* Thanks for using *"<<endl;
cout<<"*  my calculator!  *"<<endl;
cout<<"********************"<<endl;  
    return 0;
}
