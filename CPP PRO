#include<iostream>
#include<fstream>
#include<stdlib.h>
using namespace std;
class main
{
    public :
    int i;
    char sname[20];
    int sid;
    int total=0;
    string arr1[20],arr2[20],arr3[20],arr4[20],arr5[20] , ans[10];
    void gd()
    {
        cout<<"Enter your Name :"<<endl;
        cin>>sname;
        cout<<"Enter the last two digit of the roll no."<<endl;
        cin>>sid;
    }
    void sd()
    {
        ofstream fout("tanmay.txt");
        cout<<"\nName of student is : "<<sname;
        fout<<"\nName of student is : "<<sname;
        cout<<"\nEnrollment no. of student is : 20070"<<sid;
        fout<<"\nEnrollment no. of student is : 20070"<<sid;
    }
    void qu1()
    {
        char ch;
        for(i=0;i<9;i++)
        {
            if(i==0)
            {
            cout<<"\nWho is the first president of india : \nA.Dr.rajendra prasand \nB. Narendra modi \nC.mahatma gandhi\n";
            cin>>ch;
            ans[i] = ch;
            if(ch=='a' || ch=='A')
            {
                cout<<"\nYour Answer is correct \n";

            }
            else
            {
                cout<<"\nYour answer is wrong\n";
            }
            }
            if(i==1)
            {
            cout<<"\nwho is the father of indian orient : \nA.Dr.rajendra prasand \nB. Narendra modi \nC.mahatma gandhi\n";
            cin>>ch;
            ans[i] = ch;
            if(ch=='c' || ch=='C')
            {
                cout<<"\nYour Answer is correct \n";
            }
            else
            {
                cout<<"\nYour answer is wrong\n";
            }
            }
            if(i==2)
            {
            cout<<"\nName the nation animal of india : \nA. loin \nB. tiger \nC. cow\n";
            cin>>ch;
            ans[i] = ch;
            if(ch=='b' || ch=='B')
            {
                cout<<"\nYour Answer is correct \n";
            }
            else
            {
                cout<<"\nYour answer is wrong\n";
            }
            }
            if(i==3)
            {
            cout<<"\nName the national bird of india \nA. Peacock \nB. Hen \nC. Peagen\n";
            cin>>ch;
            ans[i] = ch;
            if(ch=='a' || ch=='A')
            {
                cout<<"\nYour Answer is correct \n";
            }
            else
            {
                cout<<"\nYour answer is wrong\n";
            }
            }
            if(i==4)
            {
            cout<<"\nThe taj mahal is made by : \nA. Shahjha \nB. mumtaj \nC. akbar\n";
            cin>>ch;
            ans[i] = ch;
            if(ch=='a' || ch=='A')
            {
                cout<<"\nYour Answer is correct \n";
            }
            else
            {
                cout<<"\nYour answer is wrong\n";
            }
            }
            if(i==5)
            {
            cout<<"\nRed fort is made by \nA. Akbar \nB. Babur \nC. Shivaji\n";
            cin>>ch;
            ans[i] = ch;
            if(ch=='B' || ch=='b')
            {
                cout<<"\nYour Answer is correct \n";
            }
            else
            {
                cout<<"\nYour answer is wrong\nn";
            }
            }
            if(i==6)
            {
            cout<<"\nWho is the first prime minister of india \nA. Pandit jawaharlal nehru \nB. mahatma gandhi \nC. Dr. rajendra prasad\n";
            cin>>ch;
            ans[i] = ch;
            if(ch=='a' || ch=='A')
            {
                cout<<"\nYour Answer is correct \n";
            }
            else
            {
                cout<<"\nYour answer is wrong\n";
            }
            }
            if(i==7)
            {
            cout<<"\nWho is the first prime minister of india \nA. Pandit jawaharlal nehru \nB. mahatma gandhi \nC. Dr. rajendra prasad\n";
            cin>>ch;
            ans[i] = ch;
            if(ch=='a' || ch=='A')
            {
                cout<<"\nYour Answer is correct \n";
            }
            else
            {
                cout<<"\nYour answer is wrong\n";
            }
            }
            if(i==8)
            {
            cout<<"\nWho is the first prime minister of india \nA. Pandit jawaharlal nehru \nB. mahatma gandhi \nC. Dr. rajendra prasad\n";
            cin>>ch;
            ans[i] = ch;
            if(ch=='a' || ch=='A')
            {
                cout<<"\nYour Answer is correct \n";
            }
            else
            {
                cout<<"\nYour answer is wrong\n";
            }
            }
            if(i==9)
            {
            cout<<"\nWho is the first prime minister of india \nA. Pandit jawaharlal nehru \nB. mahatma gandhi \nC. Dr. rajendra prasad\n";
            cin>>ch;
            ans[i] = ch;
            if(ch=='a' || ch=='A')
            {
                cout<<"\nYour Answer is correct \n";
            }
            else
            {
                cout<<"\nYour answer is wrong\n";
            }
            }
        }
    }
     void std()
  {
      ofstream fout("tanmay.txt",ios::app);
      cout<<" \n\nThe Data of Test is \n"<<endl;
      fout<<" \n\nThe Data of Test is \n"<<endl;
      for(i=1;i<9;i++)
      {
          cout<<"The Answer of question no. " <<i<<" is : " <<ans[i]<<endl;
          fout<<"The Answer of question no. " <<i<<" is : " <<ans[i]<<endl;
      }
  }
};
class E1   : public main
{
public:
void enter()
{
		int ch=0;
			cout<<"How many students do u want to enter??"<<endl;
			cin>>ch;
			if(total==0)
			{
			total=ch+total;
			for(int i=0;i<ch;i++)
			{
				cout<<"\nEnter the Data of student "<<i+1<<endl<<endl;
				cout<<"Enter name ";
				cin>>arr1[i];
				cout<<"Enter Roll no ";
				cin>>arr2[i];
				cout<<"Enter course ";
				cin>>arr3[i];
				cout<<"Enter year ";
				cin>>arr4[i];
				cout<<"Enter contact ";
				cin>>arr5[i];
			}
	    	}
	    	else
	    	{

	    		for(int i=total;i<ch+total;i++)
			{
				cout<<"\nEnter the Data of student "<<i+1<<endl<<endl;
				cout<<"Enter name ";
				cin>>arr1[i];
				cout<<"Enter Roll no ";
				cin>>arr2[i];
				cout<<"Enter course ";
				cin>>arr3[i];
				cout<<"Enter year ";
				cin>>arr4[i];
				cout<<"Enter contact ";
				cin>>arr5[i];
			}
			total=ch+total;
			}

}
void show()
{
	if(total==0)
	{
		cout<<"No data is entered"<<endl;
	}
	else{
		for(int i=0;i<total;i++)
	    		{
	    		cout<<"\nData of Student "<<i+1<<endl<<endl;
	    		cout<<"Name "<<arr1[i]<<endl;
	    		cout<<"Roll no "<<arr2[i]<<endl;
	    		cout<<"Course "<<arr3[i]<<endl;
	    		cout<<"year "<<arr4[i]<<endl;
	    		cout<<"Contact "<<arr5[i]<<endl;
	    	    }
	    	}
}
void search()
{
	if(total==0)
	{
		cout<<"No data is entered"<<endl;
	}
	else{
	string rollno;
				cout<<"Enter the roll no of student"<<endl;
				cin>>rollno;
				for(int i=0;i<total;i++)
				{
					if(rollno==arr2[i])
					{
						cout<<"Name "<<arr1[i]<<endl;
	    	        	cout<<"Roll no "<<arr2[i]<<endl;
	    		        cout<<"Course "<<arr3[i]<<endl;
	    		        cout<<"year "<<arr4[i]<<endl;
	    	        	cout<<"Contact "<<arr5[i]<<endl;
					}
				}
			}
}
void update()
{
	if(total==0)
	{
		cout<<"No data is entered"<<endl;
	}
	else{
		string rollno;
				cout<<"Enter the roll no of student which you want to update"<<endl;
				cin>>rollno;
					for(int i=0;i<total;i++)
				{
					if(rollno==arr2[i])
					{
						cout<<"\nPrevious data"<<endl<<endl;
						cout<<"Data of Student "<<i+1<<endl;
						cout<<"Name "<<arr1[i]<<endl;
	    	        	cout<<"Roll no "<<arr2[i]<<endl;
	    		        cout<<"Course "<<arr3[i]<<endl;
	    		        cout<<"year "<<arr4[i]<<endl;
	    	        	cout<<"Contact "<<arr5[i]<<endl;
	    	        	cout<<"\nEnter new data"<<endl<<endl;
							cout<<"Enter name ";
				            cin>>arr1[i];
				            cout<<"Enter Roll no ";
				            cin>>arr2[i];
			             	cout<<"Enter course ";
				            cin>>arr3[i];
				            cout<<"Enter year ";
				            cin>>arr4[i];
				            cout<<"Enter contact ";
				            cin>>arr5[i];
					}
				}
			}
		}
void deleterecord()
{
	if(total==0)
	{
		cout<<"No data is entered"<<endl;
	}
	else{
		int a;
	        	cout<<"Press 1 to delete all record"<<endl;
				cout<<"Press 2 to delete specific record"<<endl;
				cin>>a;
				if(a==1)
				{
					total=0;
					cout<<"All record is deleted..!!"<<endl;
				}
				else if(a==2)
				{
				string rollno;
				cout<<"Enter the roll no of student which you wanted to delete"<<endl;
				cin>>rollno;
				for(int i=0;i<total;i++)
				{
					if(rollno==arr2[i])
					{
						for(int j=i;j<total;j++)
						{
						arr1[j]=arr1[j+1];
						arr2[j]=arr2[j+1];
					    arr3[j]=arr3[j+1];
						arr4[j]=arr4[j+1];
						arr5[j]=arr5[j+1];
				     	}
					total--;
					cout<<"Your required record is deleted"<<endl;
					}
				}
				}


			else
			{
				cout<<"Invalid input";
			}
}
}
};
class CAL : public E1
{
    public :
    int status()
{
    int  f ;
    float e, p , ce, m, co;
    float total, aggregate_of_PCM , percentage , per;
    char ch;
    cout<<"  \n\n                       System By Tanmay sayare 2007056 \n\n";
    while(true)
    {
    cout<<"\nPress A-Total percentage\nPress B-To find the aggregate of PCM  \nPress C-To check your progress \nPress D-To check your backlog status\n";
    cin>>ch;
    if(ch =='a' || ch == 'A')
    {
    cout<<"\nEnter marks of five subjects outoff 100 you got : \n\n";
    cout<<"Enter the marks of english \n";
    cin>>e;
    cout<<"Enter the marks of Physic \n";
    cin>>p;
    cout<<"Enter the marks of chemistry \n";
    cin>>ce;
    cout<<"Enter the marks of mathematic \n";
    cin>>m;
    cout<<"Enter the marks of computer \n";
    cin>>co;
    total = e + p + ce + m + co;
    percentage = (total / 500.0) * 100;
    cout<<"\nPercentage = "<<percentage;
        if (percentage > 90 )
        {
            cout<<"\nExcellent"<<endl;
        }

    }
    else if(ch == 'B' || ch =='b')
    {
        cout<<"\nAggregate of PCM : \n";
        cout<<"Enter the marks of Physic \n";
        cin>>p;
        cout<<"Enter the marks of chemistry \n";
        cin>>ce;
        cout<<"Enter the marks of mathematic \n";
        cin>>m;
        total = p + m +  ce ;
        aggregate_of_PCM = total / 3;
        cout<<"\naggregate of PCM = "<<aggregate_of_PCM;
        if ( aggregate_of_PCM > 90 )
        {
            cout<<"\nExcellent";
        }


    }
    else if(ch == 'C' || ch== 'c')
    {
    cout<<"\nEnter marks of five subjects outoff 100 you got : \n";
    cout<<"Enter the marks of english \n";
    cin>>e;
    cout<<"Enter the marks of Physic \n";
    cin>>p;
    cout<<"Enter the marks of chemistry \n";
    cin>>ce;
    cout<<"Enter the marks of mathematic \n";
    cin>>m;
    cout<<"Enter the marks of computer \n";
    cin>>co;
     total = e + p + ce + m + co;
    percentage = (total / 500.0) * 100;
    cout<<"\nPercentage = "<< percentage;
        if (percentage > 60 )
        {
            cout<<"\n You are not doing well , need improvement";
        }

    }
    else if ( ch == 'D' || ch == 'd')
    {
    cout<<"\nPlease eneter your percentage\n";
     cin>>per;
        if (per <= 60 )
        {
            cout<<"\nYou are not doing well , need improvement";
            cout<<"\nYou are fail";
        }
         else if (per <= 80 )
        {
            cout<<"\n Better luck next time ";
            cout<<"\nYou are pass";
        }
        else if (per < 95 )
        {
            cout<<"\n Excellent ";
            cout<<"\nYou are passed this exam";
        }
        else if (per >= 95 )
        {
            cout<<"\n Outstanding ";
            cout<<"\nYou Cracked this exam";
        }
     }
    else
       cout<<"                              YOUR CHOICE IS WRONG PLEASE TRY AGAIN LATER !!!!!\n";
        cout<<"                                Program Executed Successfully !!!\n\n\n";
    cout<<"                              Do you want to try again\n       \nPress 1.for continue \nPress 2.for Exit "<<endl;
    cin>>f;
    if(f==1)
    {
        return true;
    }
    else if(f==2)
    {
        break;
    }
    }
    return true;
    }
};
int main()
{
	int value, pass;
	char ur[10];
	int s , l ;
	char z;
	CAL tan , *p;
	p=&tan;
	cout<<"                   WELCOME\n";
	cout<<"\nWho u are :\n 1.student \n 2.Teacher"<<endl;
	cin>>s;
	switch(s)
	{
    case 1:
        p->gd();
        while(true)
        {
        cout<<"\n\nWhat You Want to do \nA.Solve MCQs \nB.Check the status\n";
        cin>>z;
        if(z=='a'||z=='A')
    {
        p->qu1();
        cout<<"\n\n Do you want to check the Answer you have chosen \npress\n1.for yes\n2.for no"<<endl;
        cin>>l;
        p->sd();
        if(l==1)
        {
        p->sd();
        p->std();
        }
    }
        else if(z=='b'||z=='B')
    {
        p->status();
    }
        }
    break;
    case 2:
    {
        cout<<"Enter your username"<<endl;
        cin>>ur;
        cout<<"Enter your password"<<endl;
        cin>>pass;
        if(pass==1234)
        {
	while(true)
	{
	cout<<"\nPress 1 to enter data"<<endl;
	cout<<"Press 2 to show data"<<endl;
	cout<<"Press 3 to search data"<<endl;
	cout<<"Press 4 to update data"<<endl;
	cout<<"Press 5 to delete data"<<endl;
	cout<<"Press 6 to exit"<<endl;
	cin>>value;
	switch(value)
	{
		case 1:
			tan.enter();
			break;
		case 2:
			tan.show();
			break;
		case 3:
			tan.search();
			break;
		case 4:
			tan.update();
			break;
		case 5:
			tan.deleterecord();
			break;
		case 6:
			exit(0);
			break;
		default:
			cout<<"Invalid input"<<endl;
			break;
	    }
            }

        break;
        }
        else
        cout<<"Try by another way \n";
        break;
}
    default:{
            cout<<"\nYour choice is wrong\n";

    }
            break;
}
return 0;
}
