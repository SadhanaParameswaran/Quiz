# Quiz_C
#include<stdio.h>
    //declaration and initialization
    int correct_answer=0;
    int wrong_answer=0;
    double percentage;
    char name [50];
    int choice;
  
    struct student
    {
        char name [50];
        int age;
        char email [100];
        int contact;
    }s;
    
    //main function
    int main()
    {

        printf("    *****QUIZ***** \n");
        printf("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ \n");
        printf("\n");
        printf(" Before starting please do read the following instructions: \n");
        printf("* There will be three topics for this quiz, you will have to choose one of them. \n"); 
        printf("* There would be a total of 5 questions. \n");
        printf("* For each questions you would have four possible answers. \n");
        printf("* Enter the answer which you think would be right that is either a,b,c or d \n");
        printf("* Do not enter two options, it will be considerd wrong. \n");
        printf("* At the end of this quiz, your results will be displayed. \n");
        printf("* Your results would show your right answers, wrong answers and your overall percentage. \n");
        printf("\n");
        printf("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ \n");
        printf("\n");

        printf("To start this quiz enter the following details: \n");
        printf("\n");
        
        //registration
        printf("Enter your name : \n");
        scanf("%s", s.name);
        printf("\n"); 

        printf("Enter your age : \n");
        scanf("%d", &s.age);
        printf("\n");
        
        printf("Enter your email ID : \n");
        scanf("%s", s.email);
        printf("\n");

        printf("Enter your contact number : \n");
        scanf("%d", &s.contact);
        printf("\n");
        printf("\n");
        printf("\n");

        //displaying the topics for the quiz
        printf("**The topics for this quiz are** \n");
        printf("1. All about Computers \n");
        printf("2. Math fun \n");
        printf("****** \n");

        printf("Enter your choice: \n");
        scanf("%d", &choice);
        printf("\n");

        //starting swith
        switch(choice)
        {
            case 1: 
                comp();
                results();
                screen();
                certificate();
                break;

            case 2:
                math();
                results();
                screen();
                certificate();
                break;

            default:
                printf("Invalid input \n");

        }
    }

    //function to display topic 1
    void comp()
    {
        //correct options
        char b[10];
        b[0]="c";
        b[1]="a";
        b[2]="d";
        b[3]="b";
        b[4]="a";
        b[5]="c";
        b[6]="b";
        b[7]="b";
        b[8]="d";
        b[9]="c";

        printf("Your choice is : 1. All about Computers \n");
        printf("Lets start the game! \n");
        printf("\n");
        printf("\n");

        //declare an array
        char a[10];

        //display the question and options for topic 1
        printf("1.How to run Java program on the command prompt? \n");
        printf("a.javac JavaProgram \n");
        printf("b.javac JavaProgram.java \n");
        printf("c.java JavaProgram \n");
        printf("d.No one \n");
        printf("Your option is: ");
        scanf("%c", &a[0]);
        printf("\n");
        if (a[0]==b[0])
        {
            printf("Bravo! your answer is right :-) \n");
            printf("You're going on the right track!! \n");
            correct_answer++;
            printf("\n");
        }
        else
        {
            printf("Sorry your answer is wrong :-( \n");
            printf("The right answer is: c.java JavaProgram. \n");
            printf("Try your luck in the next question... \n");
            wrong_answer++;
            printf("\n");
        }

        printf("2.What is the use of the println method? \n");
        printf("a.It is used to print text on the screen with the line break. \n");
        printf( "b.It is used to print text on the screen. \n");
        printf("c.It is used to read text from keyboard. \n");
        printf("d.It is used to read text from a file. \n");
        printf("Your option is: ");
        scanf("%c", &a[1]);             
        printf("\n");
        if (a[1]==b[1])
        {
            printf("Bravo! your answer is right :-) \n");
            printf("You're going on the right track!! \n");
            correct_answer++;
            printf("\n");
        }
        else
        {
            printf("Sorry your answer is wrong :-( \n");
            printf("The right answer is:a.It is used to print text on the screen with the line break.\n");
            printf("Try your luck in the next question... \n");
            wrong_answer++;
            printf("\n");
        }

        printf("3.How to read a character from the keyboard? \n");
        printf("a.char c=System.read() \n");
        printf("b.char c=System.in.read() \n");
        printf("c.char c=(char)System.read() \n");
        printf("d.char c=(char)System.in.read() \n");
        printf("Your option is: ");
        scanf("%c", &a[2]);
        printf("\n");
        if (a[2]==b[2])
        {
            printf("Bravo! your answer is right :-) \n");
            printf("You're going on the right track!! \n");
            correct_answer++;
            printf("\n");
        }
        else
        {
            printf("Sorry your answer is wrong :-( \n");
            printf("The right answer is:d.char c=(char)System.in.read() \n");
            printf("Try your luck in the next question... \n");
            wrong_answer++;
            printf("\n");
        }

        printf("4.Which one is a single-line comment? \n");
        printf("a./... \n");
        printf("b.//... \n");
        printf("c./*... \n");
        printf("d./*...*/ \n");
        printf("Your option is: ");
        scanf("%c", &a[3]);
        printf("\n");
        if (a[3]==b[3])
        {
            printf("Bravo! your answer is right :-) \n");
            printf("You're going on the right track!! \n");
            correct_answer++;
            printf("\n");
        }
        else
        {
            printf("Sorry your answer is wrong :-( \n");
            printf("The right answer is:b.//... \n");
            printf("Try your luck in the next question... \n");
            wrong_answer++;
            printf(",\n");
        }

        printf("5.How do you declare an integer variable x? \n");
        printf("a.int x \n");
        printf("b.x as Integer \n");
        printf("c.Int[] x \n");
        printf("d.No one is correct. \n");
        printf("Your option is: ");
        scanf("%c", &a[4]);
        printf("\n");
        if (a[4]==b[4])
        {
            printf("Bravo! your answer is right :-) \n");
            printf("You're going on the right track!! \n");
            correct_answer++;
            printf("\n");
        }
        else
        {
            printf("Sorry your answer is wrong :-( \n");
            printf("The right answer is:a.int x \n");
            printf("Try your luck in the next question... \n");
            wrong_answer++;
            printf("\n");
        }

        //find the average percentage of the candidate
        percentage = correct_answer*10;

    }

    //function to display topic 2
    void math()
    {
        //correct options
        char d[10];
        d[0]="b";
        d[1]="a";
        d[2]="c";
        d[3]="b";
        d[4]="c";
        d[5]="b";
        d[6]="b";
        d[7]="a";
        d[8]="d";
        d[9]="d";  

        printf("Your choice is : 2. Math \n");
        printf("Lets start the game! \n");
        printf("\n"); 

        //declare an array
        char c[10];

        //display the question and options for topic 2
        printf("1.The average of first 50 natural numbers. \n");
        printf("a.25.30 \n");
        printf("b.25.5 \n");
        printf("c.25.00 \n");
        printf("d.12.25 \n");
        printf("Your option is: ");
        scanf("%c", &c[0]);
        printf("\n"); 
        if (c[0]==d[0])
        {
            printf("Bravo! your answer is right :-) \n");
            printf("You're going on the right track!! \n");
            correct_answer++;
            printf("\n");
        }
        else
        {
            printf("Sorry your answer is wrong :-( \n");
            printf("The right answer is:b.25.5 \n");
            printf("Try your luck in the next question... \n");
            wrong_answer++;
            printf("\n");
        }

        printf("2.A fraction which bears the same ratio to 1/27 as 3/11 bear to 5/9 is equal to? \n");
        printf("a.1/55 \n");
        printf("b.55 \n");
        printf("c.3/11 \n");
        printf("d.1/11 \n");
        printf("Your option is: ");
        scanf("%c", &c[1]);
        printf("\n"); 
        if (c[1]==d[1])
        {
            printf("Bravo! your answer is right :-) \n");
            printf("You're going on the right track!!\n");
            correct_answer++;
            printf("\n");
        }
        else
        {
            printf("Sorry your anwser is wrong :-( \n");
            printf("The right answer is:a.1/55 \n");
            printf("Try your luck in the next question... \n");
            wrong_answer++;
            printf("\n");
        }

        printf("3.The number of 3-digit numbers divisible by 6 \n");
        printf("a.149 \n");
        printf("b.166 \n");
        printf("c.150 \n");
        printf("d.151 \n");
        printf("Your option is: ");
        scanf("%c", &c[2]);
        printf("\n");
        if (c[2]==d[2])
        {
            printf("Bravo! your answer is right :-) \n");
            printf("You're going on the right track!! \n");
            correct_answer++;
            printf("\n");
        }
        else
        {
            printf("Sorry your answer is wrong :-( \n");
            printf("The right answer is:c.150 \n");
            printf("Try your luck in the next question... \n");
            wrong_answer++;
            printf("\n");
        }

        printf("4.What is 1004 divided by 2?  \n");
        printf("a.52 \n");
        printf("b.502 \n");
        printf("c.520 \n");
        printf("d.5002 \n");
        printf("Your option is: ");
        scanf("%c", &c[3]);
        printf("\n"); 
        if (c[3]==d[3])
        {
            printf("Bravo! your answer is right :-) \n");
            printf("You're going on the right track!! \n");
            correct_answer++;
            printf("\n");
        }
        else
        {
            printf("Sorry your answer is wrong :-( \n");
            printf("The right answer is:b.502 \n");
            printf("Try your luck in the next question... \n");
            wrong_answer++;
            printf("\n");
        }

        printf("5.A clock strikes once at 1 o’clock, twice at 2 o’clock, thrice at 3 o’clock and so on. How many times will it strike in 24 hours? \n");
        printf("a.78 \n");
        printf("b.136 \n");
        printf("c.156 \n");
        printf("d.196 \n");
        printf("Your option is: ");
        scanf("%c", &c[4]);
        printf("\n"); 
        if (c[4]==d[4])
        {
            printf("Bravo! your answer is right :-) \n");
            printf("You're going on the right track!! \n");
            correct_answer++;
            printf("\n");
        }
        else
        {
            printf("Sorry your answer is wrong :-( \n");
            printf("The right answer is:c.156 \n");
            printf("Try your luck in the next question...\n");
            wrong_answer++;
            printf("\n");
        }

        //find the average percentage of the candidate
        percentage = correct_answer*10;

    }

    //function display the results
    void results()
    {
        printf("^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ \n");
        printf("\n");
        printf("\n");
        printf("                                YOUR RESULTS \n");
        printf("\n");
        printf("The number of correct answers is ",correct_answer,"/10 \n");
        printf("The number of wrong answers is ",wrong_answer,"/10 \n");
        printf("Your average percentage is ",percentage,"% \n");
        printf("\n");
        printf("\n");
        printf("^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ \n");


    }

    //function to create an illusion 
    void screen()
    {
        printf("\n");
        printf("\n");
        printf("\n");
        printf("\n");
        printf("\n");
        printf("\n");
        printf("\n");
        printf("\n");
        printf("\n");
        printf("\n");
        printf("\n");
        printf("\n");
        printf("\n");
        printf("\n");
        printf("\n");
        printf("\n");
        printf("\n");
        printf("\n");
    }

    //function to display the certificate
    void certificate()
    {
        if(percentage>=80)
        {
            if(choice==1)
            {
                printf("                                    CERTIFICATE OF DISTINCTION \n");
                printf("This is to certify that ",name," has completed the online quiz on topic 1 'All About Computers' with ",percentage,"% \n");
            }
            else if(choice==2)
            {
                printf("                                    CERTIFICATE OF DISTINCTION \n");
                printf("This is to certify that ",name," has completed the online quiz on topic 2 'Math' with ",percentage,"% \n");
            }
        }
        else if(percentage<80 && percentage>=50)
        {
            if(choice==1)
            {
                printf("                                       CERTIFICATE OF MERIT \n");
                printf("This is to certify that ",name," has completed the online quiz on topic 1 'All About Computers' with ",percentage,"% \n");
            }
            else if(choice==2)
            {
                printf("                                       CERTIFICATE OF MERIT \n");
                printf("This is to certify that ",name," has completed the online quiz on topic 2 'Math' with ",percentage,"% \n");
            }
        }
        else
        {
            if(choice==1)
            {
                printf("                                     CERTIFICATE FOR PARTICIPATION \n");
                printf("This is to certify that ",name," has completed the online quiz on topic 1 'All About Computers' with ",percentage,"% \n");
            }
            else if(choice==2)
            {
                printf("                                     CERTIFICATE FOR PARTICIPATION \n");
                printf("This is to certify that ",name," has completed the online quiz on topic 2 'Math' with ",percentage,"% \n");
            }
        }
    }
