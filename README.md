#include <iostream>

using namespace std;

int main() 
{

string username1,username2,M,F,gender;
double password1,password2,number1,number2;
int choice,grade,b,c;
char a;
bool login;
login = false;


 


cout<<"\nWELCOME TO PORGRAM\n" ;
cout<<"\nCheak Not bot Press 3!!!\n";
cin>>grade;
while(grade==3){
cout<<"\n######Register######";


cout<<"\nEnter username : " ;
cin>>username1;

cout<<"\nEnter password : " ;
cin>>password1;
cout<<"\n Login to Menu ";
cout<<"\nEnter username : " ;
cin>>username2;
cout<<"\nEnter password : " ;
cin>>password2;

cout<<"\nChoose gender : M-1,F-2 ";
cin>>gender;


if(username1==username2&&password1==password2) {
	
}else{
 cout<<" worng password " ;
 }


cout<<"Press 4\n";
cin>>grade;
while(grade==4){

cout<<"Welcome To Login (Press show user)"<<endl;
cout<<"---Login Success---" <<endl;
cout<<"username : " << username2 << endl;
cout<<"password : " << password2  <<endl;
cout<<"gender   : " << gender <<endl;


cout<<"Press Menu"<< endl; 
  cout<<"1.Calculator"<<endl;
cout<<"2.Grade" <<endl;
cout<<"3 to Exit"<<endl;
cin>>grade;

switch(grade){
case 1: 
while(grade==1){ 
                        cout<<"###################### Press number example (+)###################### "<<endl; 
                        cout<<"Select to Menu " <<endl; 
                        cout<<"Enter Number : " ; 
                        cin>>number1; 
                        cout<<"Enter Number : "; 
						cin>>number2; 
                        cout<<"Select Operator"<<endl; 
                        cout<<"1.positive(+)"<<endl;
                        cout<<"2.Minus(-)"<<endl; 
                        cout<<"3.Nultipled()"<<endl;
                        cout<<"4.Divide(/)"<<endl; 
                        cout<<"5.Exit"<<endl; 
                        cout<<"6.Again"<<endl; 
                        cout<<"###################### Press Select : ###################### "<<endl; 
                        cin>>grade;
						
                           switch (grade) {
                           case 1:
                            
                            cout<<number1<<"+"<<number2<<"="<<(number1+number2)<<endl;
                            
                            break;
                         case 2:
                              cout<<number1<<"-"<<number2<<"="<<(number1-number2)<<endl;
                            break;
            
                        case 3:
                                cout<<number1<<"*"<<number2<<"="<<(number1*number2)<<endl;
                                break;
                        case 4:
                                cout<<number1<<"/"<<number2<<"="<<(number1/number2)<<endl;
                                
                                break;
                           }

   cout<<"PRESS MeNU NUMBER"<<endl;
                cout<<"1.Again" <<endl;
                cout<<"2.Exit"<<endl;
                cout<<"3.TO Register"<<endl;
                cout<<"4.Welcome To Login (Press show user)"<<endl;
                cin>>grade;
            }
				 }
			
switch (grade){
 case 2:
 while(grade==2){
 

  
cout<<"###################### Press Grade Number ######################" <<endl; 
cout<<"Enter grade"<< endl; 
cin>>grade;
if(grade>=90&& grade<100){ 
                    cout<<"A"<<endl;

            }else{
                if(grade>=80&&grade<90){
                    cout<<"B"<<endl;
                    
            }else{
                if (grade>=70&&grade<80){
                    cout<<"C"<<endl;
                    
                }else{
                    if(grade>=60&& grade<=70){
                        cout<<"D"<<endl;
                        
                    }else{
                        if(grade>0&& grade<60){
                            cout<<"F"<<endl;
                        }
                    }
                }
                
            }cout<<"PRESS MeNU NUMBER"<<endl;
            cout<<"1.Again" <<endl;
            cout<<"2.Exit"<<endl;
            cout<<"3.Register"<<endl;
            cout<<"4.Welcome To Login (Press show user)"<<endl;
            cin>>grade;
            }
    }
}
}

}

}











 


