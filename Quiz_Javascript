<html>

<head></head>

<body>

<script>

//declaration and initialization
var correct_answer = 0;
var wrong_answer = 0;
var percentage;
var name = "";
var choice = "0";
var answer; 
var x;

document.write("");
document.write("");
document.write("");
   
window.onload = main()

function main()
{
    document.write("    *******************************************QUIZ******************************************* <br>");
    document.write("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ <br>");
    document.write("<br>");
    document.write(" Before starting please do read the following instructions: <br>");
    document.write("* There will be three topics for this quiz, you will have to choose one of them. <br>");
    document.write("* There would be a total of 5 questions. <br>");
    document.write("* For each questions you would have four possible answers. <br>");
    document.write("* Enter the answer which you think would be right that is either a,b,c or d <br>");
    document.write("* Do not enter two options, it will be considerd wrong. <br>");
    document.write("* At the end of this quiz, your results will be displayed. <br>");
    document.write("* Your results would show your right answers, wrong answers and your overall percentage. <br>");
    document.write("<br>");
    document.write("~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ <br>");
    document.write("<br>");
    
    x = window. prompt("                              **********QUIZ********** \n ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~ \n \n Before starting please do read the following instructions: \n * There will be three topics for this quiz, you will have to choose one of them. \n * There would be a total of 5 questions. \n * For each questions you would have four possible answers. \n * Enter the answer which you think would be right that is either a,b,c or d \n * Do not enter two options, it will be considerd wrong. \n * At the end of this quiz, your results will be displayed. \n * Your results would show your right answers, wrong answers and your overall percentage. \n \n ~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~  \n Press any key to Continue \n");
    

    document.write("To start this quiz enter the following details: ");
    document.write("<br>");
    
    x = window. prompt("To start this quiz enter the following details:\n Press any key to Continue\n");

    //registration
    name = window. prompt("Enter your name : \n");
    document.write("Name: "+name);
    document.write("<br>");
    
    var age = window. prompt("Enter your age : \n");
    document.write("Age: "+age);
    document.write("<br>");

    var email = window. prompt("Enter your email ID : \n");
    document.write("Email ID: "+email);
    document.write("<br>");
        
    var contact = window. prompt("Enter your contact number : ");
    document.write("Contact Number: "+contact);
    document.write("<br>");
    document.write("<br>");
        
    //displaying the topics for the quiz
    document.write("******The topics for this quiz are****** <br>");
    document.write("1. All about Computers <br>");
    document.write("2. Math fun <br>");
    document.write("**************************************** <br>");

    //asking the user 
    choice = window. prompt("******The topics for this quiz are******\n 1. All about Computers\n 2. Math fun\n Enter your choice:\n");
    if(choice==1)
        document.write("The topic choosen is: All about Computers\n ");
    else
        document.write("The topic choosen is: Math fun\n ");

    //starting swith
    switch(choice)
    {
        case "1":
            comp();
            results();
            certificate();
            break;

        case "2":
            math();
            results();
            certificate();
            break;

        default:
            document.write("Invalid input <br>");
    }
}

//function to display topic 1
function comp()
{
    //correct options
    var b = new Array(5);
    b[0]="c";
    b[1]="a";
    b[2]="d";
    b[3]="b";
    b[4]="a";

    document.write("Your choice is : 1. All about Computers <br>");
    document.write("Lets start the game! <br>");
    document.write("<br>");
    
    x = window. prompt("Your choice is : 1. All about Computers \n Lets start the game! \n Press any key to continue! \n");
    
    //display the question and options for topic 1
    document.write("1.How to run Java program on the command prompt? <br>");
    document.write("a.javac JavaProgram <br>");
    document.write("b.javac JavaProgram.java <br>");
    document.write("c.java JavaProgram <br>");
    document.write("d.No one <br>");
    answer = window. prompt("1.How to run Java program on the command prompt?\n a.javac JavaProgram\n b.javac JavaProgram.java\n c.java JavaProgram\n d.No one\n Your option is:\n");
    document.write("<br>");
    if (answer == (b[0]) || answer == (b[0].toUpperCase()))
    {
        document.write("Bravo! your answer is right :-) <br>");
        document.write("You're going on the right track!! <br>");
        correct_answer++;
        document.write("<br>");
        
        x = window. prompt("Bravo! your answer is right :-)\n You're going on the right track!!\n Press any key to Continue\n");
    }
    else
    {
        document.write("Sorry your answer is wrong :-( <br>");
        document.write("The right answer is: c.java JavaProgram. <br>");
        document.write("Try your luck in the next question... <br>");
        wrong_answer++;
        document.write("<br>");
        
        x = window. prompt("Sorry your answer is wrong :-(\n The right answer is: c.java JavaProgram.\n  Try your luck in the next question...\n Press any key to Continue\n");
    }

    document.write("2.What is the use of the println method? <br>");
    document.write("a.It is used to print text on the screen with the line break. <br>");
    document.write("b.It is used to print text on the screen. <br>");
    document.write("c.It is used to read text from keyboard. <br>");
    document.write("d.It is used to read text from a file. <br>");
    answer= window. prompt("2.What is the use of the println method?\n a.It is used to print text on the screen with the line break.\n b.It is used to print text on the screen.\n c.It is used to read text from keyboard.\n d.It is used to read text from a file.\n Your option is: \n");
    document.write("<br>");
    if (answer==(b[1]) || answer == (b[1].toUpperCase()))
    {
        document.write("Bravo! your answer is right :-) <br>");
        document.write("You're going on the right track!! <br>");
        correct_answer++;
        document.write("<br>");
        
        x = window. prompt("Bravo! your answer is right :-)\n You're going on the right track!!\n Press any key to Continue\n");
    }
    else
    {
        document.write("Sorry your answer is wrong :-( <br>");
        document.write("The right answer is:a.It is used to print text on the screen with the line break. <br>");
        document.write("Try your luck in the next question... <br>");
        wrong_answer++;
        document.write("<br>");
        
        x = window. prompt("Sorry your answer is wrong :-(\n The right answer is:a.It is used to print text on the screen with the line break.\n Try your luck in the next question...\n Press any key to Continue\n");
    }

    document.write("3.How to read a character from the keyboard? <br>");
    document.write("a.char c=System.read() <br>");
    document.write("b.char c=System.in.read() <br>");
    document.write("c.char c=(char)System.read() <br>");
    document.write("d.char c=(char)System.in.read() <br>");
    answer = window. prompt("3.How to read a character from the keyboard?\n a.char c=System.read()\n b.char c=System.in.read()\n c.char c=(char)System.read()\n d.char c=(char)System.in.read()\n Your option is: \n");
    document.write("<br>");
    if (answer==(b[2]) || answer == (b[2].toUpperCase()))
    {
        document.write("Bravo! your answer is right :-) <br>");
        document.write("You're going on the right track!! <br>");
        correct_answer++;
        document.write("<br>");
        
        x = window. prompt("Bravo! your answer is right :-)\n You're going on the right track!!\n Press any key to continue\n");
    }
    else
    {
        document.write("Sorry your answer is wrong :-( <br>");
        document.write("The right answer is:d.char c=(char)System.in.read() <br>");
        document.write("Try your luck in the next question... <br>");
        wrong_answer++;
        document.write("<br>");
        
        x = window. prompt("Sorry your answer is wrong :-(\n The right answer is:d.char c=(char)System.in.read()\n Try your luck in the next question...\n Press any key to continue\n");
    }

    document.write("4.Which one is a single-line comment? <br>");
    document.write("a./... <br>");
    document.write("b.//... <br>");
    document.write("c./*... <br>");
    document.write("d./*...*/ <br>");
    answer = window. prompt("4.Which one is a single-line comment?\n a./...\n b.//...\n c./*...\n d./*...*/\n Your option is: \n");
    document.write("<br>");
    if (answer==(b[3]) || answer == (b[3].toUpperCase()))
    {
        document.write("Bravo! your answer is right :-) <br>");
        document.write("You're going on the right track!! <br>");
        correct_answer++;
        document.write("<br>");
        
        x = window. prompt("Bravo! your answer is right :-)\n You're going on the right track!!\n Press any key to continue\n");
    }
    else
    {
        document.write("Sorry your answer is wrong :-( <br>");
        document.write("The right answer is:b.//... <br>");
        document.write("Try your luck in the next question... <br>");
        wrong_answer++;
        document.write("<br>");
        
        x = window. prompt("Sorry your answer is wrong :-(\n The right answer is:b.//...\n Try your luck in the next question...\n Press any key to continue\n");
    }

    document.write("5.How do you declare an integer variable x? <br>");
    document.write("a.int x <br>");
    document.write("b.x as Integer <br>");
    document.write("c.Int[] x <br>");
    document.write("d.No one is correct. <br>");
    answer = window. prompt("5.How do you declare an integer variable x?\n a.int x\n b.x as Integer\n c.Int[] x\n d.No one is correct.\n Your option is:\n")
    document.write("<br>");
    if (answer==(b[4]) || answer == (b[4].toUpperCase()))
    {
        document.write("Bravo! your answer is right :-) <br>");
        document.write("You're going on the right track!! <br>");
        correct_answer++;
        document.write("<br>");
        
        x = window. prompt("Bravo! your answer is right :-)\n You're going on the right track!!\n Press any key to continue\n");
    }
    else
    {
        document.write("Sorry your answer is wrong :-( <br>");
        document.write("The right answer is:a.int x <br>");
        document.write("Try your luck in the next question... <br>");
        wrong_answer++;
        document.write("<br>");
        
        x = window. prompt("Sorry your answer is wrong :-(\n The right answer is:a.int x\n Try your luck in the next question...\n Press any key to continue\n");
    }
    
    //find the average percentage of the candidate
    percentage = correct_answer*20;

}

//function to display topic 2
function math()
{
    //correct options
    var d=new Array(10);
    d[0]="b";
    d[1]="a";
    d[2]="c";
    d[3]="b";
    d[4]="c";

    document.write("Your choice is : 2. Math <br>");
    document.write("Lets start the game! <br>");
    document.write("<br>");
    
    x = window. prompt("Your choice is : 2. Math \n Lets start the game! \n Press any key to continue! \n");

    //declare an array
    var c = new Array(10);

    //display the question and options for topic 2
    document.write("1.The average of first 50 natural numbers. <br>");
    document.write("a.25.30 <br>");
    document.write("b.25.5 <br>");
    document.write("c.25.00 <br>");
    document.write("d.12.25 <br>");
    c[0] = window. prompt("1.The average of first 50 natural numbers.\n a.25.30\n b.25.5\n c.25.00\n d.12.25\n Your option is: \n");
    document.write("<br>");
    if (c[0]==(d[0]) || c[0]==(d[0].toUpperCase()))
    {
        document.write("Bravo! your answer is right :-) <br>");
        document.write("You're going on the right track!! v");
        correct_answer++;
        document.write("<br>");
        
        x = window. prompt("Bravo! your answer is right :-)\n You're going on the right track!!\n Press any key to continue\n");
    }
    else
    {
        document.write("Sorry your answer is wrong :-( <br>");
        document.write("The right answer is:b.25.5 <br>");
        document.write("Try your luck in the next question... <br>");
        wrong_answer++;
        document.write("<br>");
        
        x = window. prompt("Sorry your answer is wrong :-(\n The right answer is:b.25.5\n Try your luck in the next question...\n Press any key to continue\n");
    }

    document.write("2.A fraction which bears the same ratio to 1/27 as 3/11 bear to 5/9 is equal to? <br>");
    document.write("a.1/55 <br>");
    document.write("b.55 <br>");
    document.write("c.3/11 <br>");
    document.write("d.1/11 <br>");
    c[1] = window. prompt("2.A fraction which bears the same ratio to 1/27 as 3/11 bear to 5/9 is equal to?\n a.1/55\n b.55\n c.3/11\n d.1/11\n Your option is: \n");
    document.write("<br>");
    if (c[1]==(d[1]) || c[1]==(d[1].toUpperCase()))
    {
        document.write("Bravo! your answer is right :-) <br>");
        document.write("You're going on the right track!! <br>");
        correct_answer++;
        document.write("<br>");
        
        x = window. prompt("Bravo! your answer is right :-)\n You're going on the right track!!\n Press any key to continue\n");
    }
    else
    {
        document.write("Sorry your anwser is wrong :-( <br>");
        document.write("The right answer is:a.1/55 <br>");
        document.write("Try your luck in the next question... <br>");
        wrong_answer++;
        document.write("<br>");
        
        x = window. prompt("Sorry your anwser is wrong :-(\n The right answer is:a.1/55\n Try your luck in the next question...\n Press any key to continue\n");
    }

    document.write("3.The number of 3-digit numbers divisible by 6 <br>");
    document.write("a.149 <br>");
    document.write("b.166 <br>");
    document.write("c.150 <br>");
    document.write("d.151 <br>");
    c[2] = window. prompt("3.The number of 3-digit numbers divisible by 6\n a.149\n b.166\n c.150\n d.151\n Your option is: \n");
    document.write("<br>");
    if (c[2]==(d[2]) || c[2]==(d[2].toUpperCase()))
    {
        document.write("Bravo! your answer is right :-) <br>");
        document.write("You're going on the right track!! <br>");
        correct_answer++;
        document.write("<br>");
        
        x = window. prompt("Bravo! your answer is right :-)\n You're going on the right track!!\n Press any key to continue\n");
    }
    else
    {
        document.write("Sorry your answer is wrong :-( <br>");
        document.write("The right answer is:c.150 <br>");
        document.write("Try your luck in the next question... <br>");
        wrong_answer++;
        document.write("<br>");
        
        x = window. prompt("Sorry your anwser is wrong :-(\n The right answer is:c.150\n Try your luck in the next question...\n Press any key to continue\n");
    }

    document.write("4.What is 1004 divided by 2? <br>");
    document.write("a.52 <br>");
    document.write("b.502 <br>");
    document.write("c.520 <br>");
    document.write("d.5002 <br>");
    c[3] = window. prompt("4.What is 1004 divided by 2?\n a.52\n b.502\n c.520\n d.5002\nYour option is:\n");
    document.write("<br>");
    if (c[3]==(d[3]) || c[3]==(d[3].toUpperCase()))
    {
        document.write("Bravo! your answer is right :-) <br>");
        document.write("You're going on the right track!! <br>");
        correct_answer++;
        document.write("<br>");
        
        x = window. prompt("Bravo! your answer is right :-)\n You're going on the right track!!\n Press any key to continue\n");
    }
    else    
    {
        document.write("Sorry your answer is wrong :-( <br>");
        document.write("The right answer is:b.502 <br>");
        document.write("Try your luck in the next question... <br>");
        wrong_answer++;
        document.write("<br>");
        
        x = window. prompt("Sorry your anwser is wrong :-(\n The right answer is:b.502\n Try your luck in the next question...\n Press any key to continue\n");
    }

    document.write("5.A clock strikes once at 1 o’clock, twice at 2 o’clock, thrice at 3 o’clock and so on. How many times will it strike in 24 hours? <br>");
    document.write("a.78 <br>");
    document.write("b.136 <br>");
    document.write("c.156 <br>");
    document.write("d.196 <br>");
    c[4] = window. prompt("5.A clock strikes once at 1 o’clock, twice at 2 o’clock, thrice at 3 o’clock and so on. How many times will it strike in 24 hours?\n a.78\n b.136\n c.156\n d.196\n Your option is:\n");
    document.write("<br>");
    if (c[4]==(d[4]) || c[4]==(d[4].toUpperCase()))
    {
        document.write("Bravo! your answer is right :-) <br>");
        document.write("You're going on the right track!! <br>");
        correct_answer++;
        document.write("<br>");
        
        x = window. prompt("Bravo! your answer is right :-)\n You're going on the right track!!\n Press any key to continue\n");
    }
    else
    {
        document.write("Sorry your answer is wrong :-( <br>");
        document.write("The right answer is:c.156 <br>");
        document.write("Try your luck in the next question... <br>");
        wrong_answer++;
        document.write("<br>");
        
        x = window. prompt("Sorry your anwser is wrong :-(\n The right answer is:c.156\n Try your luck in the next question...\n Press any key to continue\n");
    }
        
    //find the average percentage of the candidate
    percentage = correct_answer*20;
        
    
}

//function display the results
function results()
{
    document.write("^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <br>");
    document.write("<br>");
    document.write("<br>");
    document.write("                                YOUR RESULTS <br>");
    document.write("<br>");
    document.write("The number of correct answers is "+correct_answer+"/5 <br>");
    document.write("The number of wrong answers is "+wrong_answer+"/5 <br>");
    document.write("Your average percentage is "+percentage+"% <br>");
    document.write("<br>");
    document.write("<br>");
    document.write("^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^ <br>");


}


//function to display the certificate
function certificate()
{
    if(percentage>=80)
    {
        if(choice==1)
        {
            document.write("                                    CERTIFICATE OF DISTINCTION <br>");
            document.write("This is to certify that "+name+" has completed the online quiz on topic 1 'All About Computers' with "+percentage+"% ");
        }
        else if(choice==2)
        {
            document.write("                                    CERTIFICATE OF DISTINCTION <br>");
            document.write("This is to certify that "+name+" has completed the online quiz on topic 2 'Math' with "+percentage+"% <br>");
        }
    }
    else if(percentage<80 && percentage>=50)
    {
        if(choice==1)
        {
            document.write("                                       CERTIFICATE OF MERIT <br>");
            document.write("This is to certify that "+name+" has completed the online quiz on topic 1 'All About Computers' with "+percentage+"% <br>");
        }
        else if(choice==2)
        {
            document.write("                                       CERTIFICATE OF MERIT <br>");
            document.write("This is to certify that "+name+" has completed the online quiz on topic 2 'Math' with "+percentage+"% <br>");
        }
    }
    else
    {
        if(choice==1)
        {
            document.write("                                     CERTIFICATE FOR PARTICIPATION <br>");
            document.write("This is to certify that "+name+" has completed the online quiz on topic 1 'All About Computers' with "+percentage+"% <br>");
        }
        else if(choice==2)
        {
            document.write("                                     CERTIFICATE FOR PARTICIPATION <br>");
            document.write("This is to certify that "+name+" has completed the online quiz on topic 2 'Math' with "+percentage+"% <br>");
        }
    }
}
</script>
</body>
</html>
