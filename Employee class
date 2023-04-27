#include <iostream> 
 using namespace std; 
 class employee{ 
     public: 
       int sal; 
       int hrs; 
       void getinfo(){ 
           cout<<"Enter the salary:"; 
           cin>>sal; 
           cout<<"Enter the working hours per day:"; 
           cin>>hrs; 
           cout<<"Salary of the employee is:"<<sal<<endl; 
           cout<<"Working hours per day is:"<<hrs; 
       } 
       void addsal(){ 
           if (sal<500){ 
               sal+=10; 
           } 
            
       } 
       int addwork(){ 
           if (hrs>6){ 
               sal+=5; 
           } 
           return sal; 
           
           
       } 
        
 }; 
 int main() { 
     employee emp1; 
     emp1.getinfo(); 
     emp1.addsal(); 
     cout<<"The final salary of the employee is:"<<emp1.addwork(); 
     return 0; 
 }
