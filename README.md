contructor

/*Creating 4 variable and assign two different value different value to each variable in the contructor and then find
 the average of the variable in the pair of two and also use destructor to distory the data*/
#include<iostream>
using namespace std;
class average
{
	private:
		float  a;
		float b;
	    float  c;
	    float  d;
		public:
			average()
			{
				a=4;
				b=3;
				c=2;
				d=5;
				float average;
				average=a+b/2;
				cout<<"The average of the a and b is "<<average<<endl;
				average=c+d/2;
				cout<<"The average of the c and d is "<<average<<endl;
			}
			~average()
			{
				cout<<"The data is destructed succefully "<<endl;
			}	
		};
		int main()
		{
			average a1;
			
		}

  ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Paramaterize constructor
/*Write a class that has marks and grade as data members. A constructor with two
parameters inialize data members with the given value and member fucntion show display the value of data member 
Create two objects and display the values*/
#include<iostream>
using namespace std;
class Student 
{
	private:
		int marks;
		char grade;
		public:
			Student(int a, char b)
			{
				marks=a;
				grade=b; 
			}
			void display()
			{
				cout<<"The Marks of the student is :"<<marks<<endl;
				cout<<"The grade of the student is :"<<grade<<endl;
			}
			~Student()
			{
				cout<<"The data has been destructed succesfully "<<endl;
			}
};
int main()
{
	Student obj(100,'A');
	obj.display();
}

  
