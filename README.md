/*#include<iostream>
int main(){
    std::cout<<"Hello,World"<<std::endl;
    return 0;
}
*/
#include <iostream>
#include <string>

using namespace std;
int main(){ 
    int age = 20;
    double price = 29.29;
    float weigth = 75.5f;
    char grade = 'A';
    bool isStudent = true;
    string name = "Jalleine Gunday";

//geting input using cout---
cout << "Name: "<< name << endl;
cout << "Age: "<< age << endl;
cout << "Price: "<< price << endl;
cout << "Weigth: "<< weigth << endl;
cout << "Grade: "<< grade << endl;
cout << "IsStudent: "<< isStudent << endl;

string userCity;
cout<<"/nEnter your City:";
cin>> userCity;
cout<<"You live in:"<<userCity<<endl;

cin.ignore();
//character from previous cin
string fullSentence;
cout<<"Enter a Sentence about yourself:";
getline(cin,fullSentence);
cout<<"You said:"<<fullSentence<<endl;

return 0;

//Control Flow(if/else, switch,loops)
#include<iostream>
using namespace std;

//if/else if/else condition
int score;
cout << "Enter your exam score: ";
cin >> score;

if (score >= 90) {
    cout << "Grade: A" << endl;
} 
else if (score >= 80) {
    cout << "Grade: B" << endl;
} 
else {
    cout << "Grade: C or lower" << endl;
}
    

int day;
    cout<<"Enter a day number(1-7):";
    cin>>day;

switch (day){
    case 1: cout<<"Monday"<< endl;break;
    case 2: cout<<"Tuesday"<<endl;break;
    case 3: cout<<"Wednesday"<<endl;break;
    case 4: cout<<"Thursday"<<endl;break;
    case 5: cout<<"Friday"<<endl;break;
    case 6: cout<<"Saturday"<<endl;break;
    case 7: cout<<"Sunday"<<endl;break;
    default : cout<<"Invalid Day"<<endl;break;

//for loop
 cout<< "/nCounting 1 to 5 with a for loop:"<<endl;
    for(int i = 1; i<=5; i++){
        cout<<i<<"";
    }
        cout<<endl;
    
//while loop 
cout<<"nCounting down from 5 with a loop:"<<endl;
    int n = 5;
    while(n>0){
        cout<< n << " ";
        n--;
    }
        cout<<endl;

//do while loop 
    cout <<"/ndo while example:"<<endl;
    int x = 0;
    do{
        cout<< "x = "<< x <<endl;
        x++;
    }while(x < 3);

//break and continue 
cout << "\nSkipping 3 using continue, stopping at 7 using break" << endl;
    for(int i =1; i<=10; i++){
        if(i == 3) continue;
        if(i == 7) break;
        cout<< i << " ";
    }
    cout << endl;
    return 0;
    
    }
}






















