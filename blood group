#include<stdio.h>

void BloodRequests(){
	int n=6,i;
	char requests[50][100]={"Sai","Vamsi","Niteesh","Varun","Sandeep","Charan"};
	for(i=0;i<n;i++){
		printf("%s ",requests[i]);
	}
}

void Donors(){
	int n=8,i;
	char donors1[50][100]={"Balaji : A+","Mahesh : AB+","Pawan : O+","Manoj : B+","Praveen : A-","Ramesh : B-","Kalyan : O-","Tarak : AB-"};
	for(i=0;i<n;i++){
		printf("%s ",donors1[i]);
	}
}

void registration(){
    int age,number,OTP;
	char name,blood[20];
	printf("\nEnter your Name: ");
	scanf("%s",&name);
	printf("\nEnter your blood group: ");
	scanf("%s",&blood);
	printf("\nEnter your Age: ");
	scanf("%d",&age);
	if(age>45||age<18)
	{
	    printf("\nYou are not eligible for blood Donation");
	}
	
	printf("\nEnter your Mobile number :");
	scanf("%d",&number);
	printf("\nEnter OTP for completing your registration :");
	scanf("%d",&OTP);
	printf("\nNOTE : If you are an Alcoholic, then you are not eligible for blood donation ");
	printf("\nYour Registration done successfully");
}
int main(){
    int n,login,option1,option2;
    char hospital[100];
    printf("\nWelcome to XYZ NGO's blood donation Application ");
    printf("\nUser=1, Admin=2");
    printf("\nType of your login: ");
    scanf("%d",&login);
    switch(login)
    {
        
		case 1:
			printf("\nYou known as an User ");
			printf("\nClick 1- To donate Blood");
			printf("\nClick 2- For requesting Blood");
			printf("\nClick 3- Registration Purpose");
			printf("\nEnter the choice you want: \n");
			scanf("%d",&option1);
			char BloodGroup;
			switch(option1)
			{
				case 1:
				    printf("\nBlood you are willing to donate: ");
					scanf("%s",&BloodGroup);
					printf("\nYou can donate Blood in the following Hospitals : ");
					printf("\nPulse Hospital,66773,Pogathota,Nellore");
					printf("\nLotus Hospital,87410,Vijayamahal Centre,Nellore");
					printf("\nKims Hospital,11003,Dargamitta,Nellore");
					printf("\nNarayana Hospital,52134,Balaji Nagar,Nellore");
					printf("\nSmile Super Speciality Hospital,89103,B.V.Nagar,Nellore");
					printf("\nBrain Wave Hospital,71843,Kishan Nagar,Nellore");
					printf("\nYour request for blood donation has been sent successfully");
					
					break;
				case 2:
					printf("\nEnter Blood group you need :");
					scanf("%s",&BloodGroup);
					printf("Your request for blood has been sent successfully ");
					
					break;
				case 3:
				    printf("\nMake a Registration: ");
					registration();
					
			}
		    break;
			
			case 2:
        	printf("\nYou known as an Admin ");
        	printf("\nClick 1- for Adding Hospital Names");
        	printf("\nClick 2- List of Donors");
        	printf("\nClick 3- to Check the Request List");
        	printf("\nEnter the choice you want: ");
        	scanf("%d",&option2);
        	switch(option2)
        	{
        		case 1:
        		    printf("\nEnter the Hospitals name that you want to add : ");
        		    scanf("%s",&hospital);
        		   
        		    printf("\nFollowing Hospitals are added successfully : %s",&hospital);
        		    

        			break;
        		case 2:
        			printf("\nList of Donors: ");
        			Donors();

        			break;
        		case 3:
        			printf("\nRequest list: ");
        			BloodRequests();
        			break;
			}
			
    }
}
