import java.util.*;
public class Project
{
    //declaration and initialization
    int correct_answer=0;
    int wrong_answer=0;
    double percentage;
    static String name;
    static int choice;

    //main function
    public static void main()
    {

        //declaration
        Scanner sc = new Scanner(System.in);

        System.out.println("    *******************************************QUIZ*******************************************");

        System.out.println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");
        System.out.println();
        System.out.println(" Before starting please do read the following instructions:");
        System.out.println("* There will be three topics for this quiz, you will have to choose one of them."); ;
        System.out.println("* There would be a total of 10 questions.");
        System.out.println("* For each questions you would have four possible answers.");
        System.out.println("* Enter the answer which you think would be right that is either a,b,c or d");
        System.out.println("* Do not enter two options, it will be considerd wrong.");
        System.out.println("* At the end of this quiz, your results will be displayed.");
        System.out.println("* Your results would show your right answers, wrong answers and your overall percentage.");
        System.out.println();
        System.out.println("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~");
        System.out.println();

        System.out.println("To start this quiz enter the following details: ");
        System.out.println();

        //registration
        System.out.println("Enter your name : ");
        name = sc.nextLine();
        System.out.println(); 

        System.out.println("Enter your age : ");
        int age = sc.nextInt();
        System.out.println();
        sc.nextLine();

        System.out.println("Enter your email ID : ");
        String email = sc.next();
        System.out.println();
        sc.nextLine();

        System.out.println("Enter your contact number : ");
        long contact = sc.nextLong();
        System.out.println();
        System.out.println();

        //displaying the topics for the quiz
        System.out.println("******The topics for this quiz are******");
        System.out.println("1. All about Computers");
        System.out.println("2. Math fun");
        System.out.println("****************************************");

        System.out.println("Enter your choice: ");
        choice = sc.nextInt();  

        //starting swith
        switch(choice)
        {
            case 1: 
            Project p1 = new Project();
            p1.comp();
            p1.results();
            p1.screen();
            p1.certificate();

            break;

            case 2:
            Project p2 = new Project();
            p2.math();
            p2.results();
            p2.screen();
            p2.certificate();
            break;

            default:
            System.out.println("Invalid input");

        }
    }

    //function to display topic 1
    void comp()
    {
        //declaration
        Scanner sc=new Scanner(System.in);

        //correct options
        String b[]= new String[10];
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

        System.out.println("Your choice is : 1. All about Computers");
        System.out.println("Lets start the game!");
        System.out.println();

        //declare an array
        String a[] = new String[10];

        //display the question and options for topic 1
        System.out.println("1.How to run Java program on the command prompt?");
        System.out.println("a.javac JavaProgram");
        System.out.println("b.javac JavaProgram.java");
        System.out.println("c.java JavaProgram");
        System.out.println("d.No one");
        System.out.print("Your option is: ");
        a[0]=sc.next();
        System.out.println();
        if (a[0].equals(b[0]))
        {
            System.out.println("Bravo! your answer is right :-) ");
            System.out.println("You're going on the right track!!");
            correct_answer++;
            System.out.println();
        }
        else
        {
            System.out.println("Sorry your answer is wrong :-( ");
            System.out.println("The right answer is: c.java JavaProgram.");
            System.out.println("Try your luck in the next question...");
            wrong_answer++;
            System.out.println();
        }

        System.out.println("2.What is the use of the println method?");
        System.out.println("a.It is used to print text on the screen with the line break.");
        System.out.println( "b.It is used to print text on the screen.");
        System.out.println("c.It is used to read text from keyboard.");
        System.out.println("d.It is used to read text from a file.");
        System.out.print("Your option is: ");
        a[1]=sc.next();             
        System.out.println();
        if (a[1].equals(b[1]))
        {
            System.out.println("Bravo! your answer is right :-) ");
            System.out.println("You're going on the right track!!");
            correct_answer++;
            System.out.println();
        }
        else
        {
            System.out.println("Sorry your answer is wrong :-( ");
            System.out.println("The right answer is:a.It is used to print text on the screen with the line break.");
            System.out.println("Try your luck in the next question...");
            wrong_answer++;
            System.out.println();
        }

        System.out.println("3.How to read a character from the keyboard?");
        System.out.println("a.char c=System.read()");
        System.out.println("b.char c=System.in.read()");
        System.out.println("c.char c=(char)System.read()");
        System.out.println("d.char c=(char)System.in.read()");
        System.out.print("Your option is: ");
        a[2]=sc.next();
        System.out.println();
        if (a[2].equals(b[2]))
        {
            System.out.println("Bravo! your answer is right :-) ");
            System.out.println("You're going on the right track!!");
            correct_answer++;
            System.out.println();
        }
        else
        {
            System.out.println("Sorry your answer is wrong :-( ");
            System.out.println("The right answer is:d.char c=(char)System.in.read()");
            System.out.println("Try your luck in the next question...");
            wrong_answer++;
            System.out.println();
        }

        System.out.println("4.Which one is a single-line comment?");
        System.out.println("a./...");
        System.out.println("b.//...");
        System.out.println("c./*...");
        System.out.println("d./*...*/");
        System.out.print("Your option is: ");
        a[3]=sc.next();
        System.out.println();
        if (a[3].equals(b[3]))
        {
            System.out.println("Bravo! your answer is right :-) ");
            System.out.println("You're going on the right track!!");
            correct_answer++;
            System.out.println();
        }
        else
        {
            System.out.println("Sorry your answer is wrong :-( ");
            System.out.println("The right answer is:b.//...");
            System.out.println("Try your luck in the next question...");
            wrong_answer++;
            System.out.println();
        }

        System.out.println("5.How do you declare an integer variable x?");
        System.out.println("a.int x");
        System.out.println("b.x as Integer");
        System.out.println("c.Int[] x");
        System.out.println("d.No one is correct.");
        System.out.print("Your option is: ");
        a[4]=sc.next();
        System.out.println();
        if (a[4].equals(b[4]))
        {
            System.out.println("Bravo! your answer is right :-) ");
            System.out.println("You're going on the right track!!");
            correct_answer++;
            System.out.println();
        }
        else
        {
            System.out.println("Sorry your answer is wrong :-( ");
            System.out.println("The right answer is:a.int x");
            System.out.println("Try your luck in the next question...");
            wrong_answer++;
            System.out.println();
        }
        //find the average percentage of the candidate
        percentage = correct_answer*10;

    }

    //function to display topic 2
    void math()
    {
        //declaration
        Scanner sc=new Scanner(System.in);

        //correct options
        String d[]= new String[10];
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

        System.out.println("Your choice is : 2. Math");
        System.out.println("Lets start the game!");
        System.out.println(); 

        //declare an array
        String c[] = new String[10];

        //display the question and options for topic 2
        System.out.println("1.The average of first 50 natural numbers. ");
        System.out.println("a.25.30");
        System.out.println("b.25.5");
        System.out.println("c.25.00");
        System.out.println("d.12.25");
        System.out.print("Your option is: ");
        c[0]=sc.next();
        System.out.println(); 
        if (c[0].equals(d[0]))
        {
            System.out.println("Bravo! your answer is right :-) ");
            System.out.println("You're going on the right track!!");
            correct_answer++;
            System.out.println();
        }
        else
        {
            System.out.println("Sorry your answer is wrong :-( ");
            System.out.println("The right answer is:b.25.5");
            System.out.println("Try your luck in the next question...");
            wrong_answer++;
            System.out.println();
        }

        System.out.println("2.A fraction which bears the same ratio to 1/27 as 3/11 bear to 5/9 is equal to?");
        System.out.println("a.1/55");
        System.out.println("b.55");
        System.out.println("c.3/11");
        System.out.println("d.1/11");
        System.out.print("Your option is: ");
        c[1]=sc.next();
        System.out.println(); 
        if (c[1].equals(d[1]))
        {
            System.out.println("Bravo! your answer is right :-) ");
            System.out.println("You're going on the right track!!");
            correct_answer++;
            System.out.println();
        }
        else
        {
            System.out.println("Sorry your anwser is wrong :-( ");
            System.out.println("The right answer is:a.1/55");
            System.out.println("Try your luck in the next question...");
            wrong_answer++;
            System.out.println();
        }

        System.out.println("3.The number of 3-digit numbers divisible by 6 ");
        System.out.println("a.149");
        System.out.println("b.166");
        System.out.println("c.150");
        System.out.println("d.151");
        System.out.print("Your option is: ");
        c[2]=sc.next();
        System.out.println();
        if (c[2].equals(d[2]))
        {
            System.out.println("Bravo! your answer is right :-) ");
            System.out.println("You're going on the right track!!");
            correct_answer++;
            System.out.println();
        }
        else
        {
            System.out.println("Sorry your answer is wrong :-( ");
            System.out.println("The right answer is:c.150");
            System.out.println("Try your luck in the next question...");
            wrong_answer++;
            System.out.println();
        }

        System.out.println("4.What is 1004 divided by 2?");
        System.out.println("a.52");
        System.out.println("b.502");
        System.out.println("c.520");
        System.out.println("d.5002");
        System.out.print("Your option is: ");
        c[3]=sc.next();
        System.out.println(); 
        if (c[3].equals(d[3]))
        {
            System.out.println("Bravo! your answer is right :-) ");
            System.out.println("You're going on the right track!!");
            correct_answer++;
            System.out.println();
        }
        else
        {
            System.out.println("Sorry your answer is wrong :-( ");
            System.out.println("The right answer is:b.502");
            System.out.println("Try your luck in the next question...");
            wrong_answer++;
            System.out.println();
        }

        System.out.println("5.A clock strikes once at 1 o’clock, twice at 2 o’clock, thrice at 3 o’clock and so on. How many times will it strike in 24 hours?");
        System.out.println("a.78");
        System.out.println("b.136");
        System.out.println("c.156");
        System.out.println("d.196");
        System.out.print("Your option is: ");
        c[4]=sc.next();
        System.out.println(); 
        if (c[4].equals(d[4]))
        {
            System.out.println("Bravo! your answer is right :-) ");
            System.out.println("You're going on the right track!!");
            correct_answer++;
            System.out.println();
        }
        else
        {
            System.out.println("Sorry your answer is wrong :-( ");
            System.out.println("The right answer is:c.156");
            System.out.println("Try your luck in the next question...");
            wrong_answer++;
            System.out.println();
        }
        //find the average percentage of the candidate
        percentage = correct_answer*10;

    }
    //function display the results
    void results()
    {
        System.out.println("^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^");
        System.out.println();
        System.out.println();
        System.out.println("                                YOUR RESULTS");
        System.out.println();
        System.out.println("The number of correct answers is "+correct_answer+"/10");
        System.out.println("The number of wrong answers is "+wrong_answer+"/10");
        System.out.println("Your average percentage is "+percentage+"%");
        System.out.println();
        System.out.println();
        System.out.println("^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^");


    }

    //function to create an illusion 
    void screen()
    {
        System.out.println();
        System.out.println();
        System.out.println();
        System.out.println();
        System.out.println();
        System.out.println();
        System.out.println();
        System.out.println();
        System.out.println();
        System.out.println();
        System.out.println();
        System.out.println();
        System.out.println();
        System.out.println();
        System.out.println();
        System.out.println();
        System.out.println();
        System.out.println();
    }

    //function to display the certificate
    void certificate()
    {
        if(percentage>=80)
        {
            if(choice==1)
            {
                System.out.println("                                    CERTIFICATE OF DISTINCTION");
                System.out.println("This is to certify that "+name+" has completed the online quiz on topic 1 'All About Computers' with "+percentage+"%");
            }
            else if(choice==2)
            {
                System.out.println("                                    CERTIFICATE OF DISTINCTION");
                System.out.println("This is to certify that "+name+" has completed the online quiz on topic 2 'Math' with "+percentage+"%");
            }
        }
        else if(percentage<80 && percentage>=50)
        {
            if(choice==1)
            {
                System.out.println("                                       CERTIFICATE OF MERIT");
                System.out.println("This is to certify that "+name+" has completed the online quiz on topic 1 'All About Computers' with "+percentage+"%");
            }
            else if(choice==2)
            {
                System.out.println("                                       CERTIFICATE OF MERIT");
                System.out.println("This is to certify that "+name+" has completed the online quiz on topic 2 'Math' with "+percentage+"%");
            }
        }
        else
        {
            if(choice==1)
            {
                System.out.println("                                     CERTIFICATE FOR PARTICIPATION");
                System.out.println("This is to certify that "+name+" has completed the online quiz on topic 1 'All About Computers' with "+percentage+"%");
            }
            else if(choice==2)
            {
                System.out.println("                                     CERTIFICATE FOR PARTICIPATION");
                System.out.println("This is to certify that "+name+" has completed the online quiz on topic 2 'Math' with "+percentage+"%");
            }
        }
    }
}
