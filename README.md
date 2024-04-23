# Welcome to Kaira's repository ❤💖

## I am curretly studying new programming languages 💪🤞
 Java and Python. 
 I am learing in WoTech program.
 
 2. Lesson

```java

public class Main {
  public static void main(String[] args) {

    // This is a string
    var text = "This is a random text";
    text = "this is another text";
    text = "March";

    // boolean - lightswitch
    var isDisabled = false;
    isDisabled = true;

    var number = 5;
    number = number + 7;  
    
    text= text + " "+ number;
    
    //float, string, character
    var interestingNumber = 100.5f;

    var mixedInterestingNumber = interestingNumber + number; 
    

    System.out.println(text);
    System.out.println(isDisabled);
    System.out.println(number);
    System.out.println(interestingNumber);
    System.out.println(mixedInterestingNumber);
    
  }
```
2. lesson Team work

```java
public class Main {
  public static void main(String[] args) {

    // This is a string
    var text = "This is a random text";
    text = "this is another text";
    text = "March";

    // boolean - lightswitch
    var isDisabled = false;
    isDisabled = true;

    var number = 5;
    number = number + 7;  
    
    text= text + " "+ number;
    
    //float, string, character
    var interestingNumber = 100.5f;

    var mixedInterestingNumber = interestingNumber + number; 

    var age = 24.6f;
    var gender = "female";
    var name = "Jane";
    var occupation = "Student";
    var dream = "To be a programmer";
    var bankaccount = "UK3920MISA93200";

    
    var interestingtext = " Jane was Student at the age of 24.6 but as she grew up she realized that she wanted to be a programmer. But as an student she did not have money to buy a computer. So she decided to open a bank account. Her ban account is UK3920MISA93200. Send her money so she can fulfill her dream.";
    
    
    
    System.out.println("Students age:" + age);
      System.out.println("Students gender:" + gender);
      System.out.println("Students name:" + name);
      System.out.println("Students occupation:" + occupation);
      System.out.println("Students dream:" + dream); 
      System.out.println("Students bankaccount:" + bankaccount);

    
    System.out.println(interestingtext);
    
  }

 
}
```
Lesson 3
 ```java
public class Main {
  public static void main(String[] args) {
    

    String username = "Daiga";

    if(username !="Elchin"){
      System.out.println("You can come to party");
    }else{
      System.out.println("Go home!");

    }

  }
}

and

public class Main {
  public static void main(String[] args) {
    String studentName = "Anna";
    int yearOfSchool = 12;
    double studentAge = 17;
    double grade = 9.7;
    boolean olympicsWinner = false;
    boolean isAgeEligible = studentAge >= 18;
    boolean isGradeEligible = grade >= 8;

    if (isAgeEligible && (isGradeEligible || olympicsWinner)) {
      System.out.println("You are accepted!");
    } else {
      System.out.println("You are not accepted. Reasons:");

      if (!isAgeEligible) {
        System.out.println("- You are not eligible due to age.");
      }
      if (!isGradeEligible && !olympicsWinner) {
        System.out.println("- You are not eligible due to insufficient grade.");
      }
      if (!olympicsWinner && isAgeEligible && isGradeEligible) {
        System.out.println("- You are not eligible due to not being an Olympics winner.");
      }
    }
  }
}

and
public class Main {
  public static void main(String[] args) {
    String studentName = "Anna";
    int yearOfSchool = 12;
    double studentAge = 18.5;
    double grade = 6.8;
    boolean olympicsWinner = true;
    
    // Our condition
    // Student age must be 18 or older
    // AND
    // grade must be more than or equal to 8
    //OR must win some olympiad
    
    boolean isAgeEligible = studentAge >= 18;
    boolean isGradeEligible = grade >= 8;


    if(isAgeEligible && (isGradeEligible || olympicsWinner)){
      System.out.println("You are accepted!");
    }else{
      System.out.println("Try next time!");
    }

  }
}

```
Lesson 4 

```java
public class Main {
  public static void main(String[] args) {
    String studentName = "Anna";
    int yearOfSchool = 12;
    double studentAge = 17.6;
    double grade = 9.2;

    // Our condition
    // Student age must be 18 or older
    // AND
    // grade must be more than or equal to 8
    boolean isAgeEligible = studentAge >= 18;
    boolean isGradeEligible = grade >= 8;

    
    if(isAgeEligible && isGradeEligible){
      System.out.println("You are accepted!");
    }else{
      System.out.println("Try next time!");
    }
    
  }
}

```
Lesson 5

```java
public class Main {
public static void main(String[] args) {    
  //System.out.println("Hello world!");
  // winter, spring, summer, autumn
  // warm jacket, t-shirt, swimming suite, rain coat
  String season = "spring";

  if (season == "winter") {
    System.out.println("Wear a warm jacket!");
  }
  else if (season == "spring") {
    System.out.println("Wear a T-shirt!");
  }
  else if (season == "summer") {
    System.out.println("Wear a swimming suite!");
  }
  else if (season == "autumn") {
    System.out.println("Wear a rain coat!");
  }   
  else {
  System.out.println("I do not recongnize this season!");
}
  double temp = -15.0;

  if (temp <= 5) {
    System.out.println("Wear super warm");
  }
  else if (temp <= 15) {
    System.out.println("Wear warm");
  }
  else if (temp <= 30) {
    System.out.println("Wear normal");
  }
  else {
    System.out.println("You need cooling");
  }
}


  
}
```
Lesson 6 
```java

public class Main {
  public static void main(String[] args) {
    System.out.println("Let's go and check out what is in the fridge!");
    var isFridgeOpen = false;
    String result;

    if (isFridgeOpen) {
      var item1 = "Cheese";
      var item2 = "Milk";
      var item3 = "Eggs";
      result = item1 + item2 + item3;
    } else {
      result = "Fridge is closed, open the fridge";
    }

    System.out.println(result);
    // ERROR System.out.println(item1);
  }
}

public class Main {
    
  public static void main(String[] args){  
    int mainValue = 14;
    System.out.println(mainValue);
    firstMethod();
    secondMethod();

    //authenticateUser();
    //verifyUser();
    //prepareMessage();
    //sendEmailToUser();
    //registerInDatabase();
  }

  ```

Lesson 7 

```java 
public class Main {
  public static void main(String[] args) {

    System.out.println("Hello world!");

    int i = 1; // 1
          //1 <= 10 -> TRUE
          //2 <= 10 -> TRUE
          //3 <= 10 -> TRUE
          //...
          //11 <= 10 -> FALSE
    while (i <= 10) {
      String result = ""; // Result
      if (i % 2 == 0) { //Odd or even
        result = "even";
      } else {
        result = "odd";
      }
                        //1 odd
                        //2 even
      System.out.println(i + " " + result);
      i = i + 1; // i = i + 1;
      //i = 1 + 1;
      //i = 2 + 1;
      //i = 3 + 1;
    }
  }
}

and

import java.util.Scanner;

public class Main {
  public static void main(String[] args) {

    Scanner scanner = new Scanner(System.in); //Opening a channel

    int number; //number = 7
    number = scanner.nextInt(); // Waits for us to provide an integer
    System.out.println("This is the provided number:" + number);
    
    scanner.close(); // Closing the channel
    //scanner.nextLine(); // Waits for us to provide a string until pressed enter 
  }
}

and

import java.util.Scanner;

public class Main {
  public static void main(String[] args) {

    Scanner scanner = new Scanner(System.in); //Opening a channel
    System.out.println("Hello!");
    int age; //number = 7
    System.out.println("What is your age?");
    age = scanner.nextInt(); // Waits for us to provide an integer
    System.out.println("The users age is:" + age);

    //
    
    scanner.close(); // Closing the channel
    //scanner.nextLine(); // Waits for us to provide a string until pressed enter 

  }
}
and

import java.util.Scanner;

public class Main {
  public static void main(String[] args) {

    Scanner scanner = new Scanner(System.in); //Opening a channel
    System.out.println("Write a number");
    int a = scanner.nextInt();
    System.out.println("Write an another number");
    int b = scanner.nextInt();
    
    System.out.println("A sum of A and B is " + (a + b));
    
    scanner.close(); // Closing the channel
    //scanner.nextLine(); // Waits for us to provide a string until pressed enter 
  }
}
and

import java.util.Scanner;

public class Main {
  public static void main(String[] args) {

    int amountOfTimesToDuck = 10;
    while(amountOfTimesToDuck !=0) {
      System.out.println("Duck");
      amountOfTimesToDuck = amountOfTimesToDuck -1;
    }
    
  }
}

and

public class Main {
  public static void main(String[] args) {
    
    System.out.println("Hello world!");

    int i = 1; 
    boolean isEven = false; // First NUMBER IS ALWAYS ODD
    // isEven is True for second Number
    //Counts from 0 to 10
    //Provides whether or not the number is even or odd
    
    while (i <= 10) {
      String result = "";
      if (isEven == true){
        result = "even";
      } else {
        result = "odd";
      }
      System.out.println(i + " " + result);
      i = i + 1;
      isEven = !isEven; 
      // isEven == true -> isEven = false
      // isEven == false -> isEven = true;
    }
  }
}

and

public class Main {
  public static void main(String[] args) {

    int i = 1;
    boolean isEven = false;
    // counts from 1 to 10
    // provides infor whether or not the number is even or odd
    while (i <= 10) {
      String evenOrOdd = "";
      if(isEven == true){
        evenOrOdd = "Even";
      } else{
        evenOrOdd = "Odd";
      }
      System.out.println(i + " " + evenOrOdd);
      i = i+1;
      isEven = !isEven;
    } 
  }
}

and

public class Main {
  public static void main(String[] args) {

    System.out.println("Hello world!");

    int i = 1; // 1
          //1 <= 10 -> TRUE
          //2 <= 10 -> TRUE
          //3 <= 10 -> TRUE
          //...
          //11 <= 10 -> FALSE
    while (i <= 10) {
      String result = ""; // Result
      if (i % 2 == 0) { //Odd or even
        result = "even";
      } else {
        result = "odd";
      }
                        //1 odd
                        //2 even
      System.out.println(i + " " + result);
      i = i + 1; // i = i + 1;
      //i = 1 + 1;
      //i = 2 + 1;
      //i = 3 + 1;
    }
  }
}

and

   int i = 1;
    while (i <= 10) {
      // Start action

      System.out.println(i);
      // End action
      i = i + 1;
    }


    for (int i = 1; i <= 10; i = i + 1){
      System.out.println(i);
    }

```
Lesson 7 homework. I do not have all previous homeworks at notepad I need to search

```java
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int randomNumber = (int) (Math.random() * 101); // Generates a random number between 0 and 100
        int guess;

        System.out.println("Welcome to the Guessing Game!");
        System.out.println("I've chosen a number between 0 and 100. Try to guess it!");

        do {
            System.out.print("Enter your guess: ");
            guess = scanner.nextInt();

            if (guess < randomNumber) {
                System.out.println("The number is bigger than your guess. Try again!");
            } else if (guess > randomNumber) {
                System.out.println("The number is smaller than your guess. Try again!");
            }
        } while (guess != randomNumber);

        System.out.println("Congratulations! You've guessed the number " + randomNumber + " correctly!");
        scanner.close();
    }
}
```
Lesson 8

```java
import java.util.Scanner;
public class Main {
  public static void main(String[] args) {
    Scanner scanner = new Scanner (System.in);
     int number = scanner.nextInt();

      //1.Get user input - x 
      //2.Create a loop that runs x amount of times 
     //3.Inside the loop, print_symbol i times 
    String result ="";
    for(int i = 1; i <= number; i++){
      result= result + "_";
      System.out.println(result);
    }
    scanner.close();
  }

}

import java.util.Scanner;

public class Main {
  public static void main(String[] args) {
    Scanner scanner = new Scanner(System.in); // Opening a channel for user input
    int number = scanner.nextInt(); // Waiting for a number

    String result = ""; // an empty string
                    // 1 <= 5
    for (int i = 1; i <= number; i++) { // We do action before first cycle; condition for cycle; action after every cycle
      result = result + "_";
      System.out.println(result);
    }

    scanner.close();
  }
}
```
Lesson 9

```java
import java.util.Scanner;

public class Main {
  public static void main(String[] args) {

    Scanner scanner = new Scanner(System.in);
    System.out.println("Please enter a number: ");

    int number = scanner.nextInt(); //15

    for(int i = 1; i <= number; i++){
      // 1 2 3 4 5 ... 15

      // 7
      String result = "";
      if (i % 3 == 0){ //15
        result += "Wo"; //Add Wo to the result
      } 
      if (i % 5 == 0){ // 5 10 15
        result += "Tech";
      } 
      
      if (result == ""){ 
        //result = String.valueOf(i); //Then result = i (number)
        System.out.println(i);
      }else{
        System.out.println(result);
      }
      
      

      scanner.close();
    }
  }
```
Lesson 10 
```java
/*
A step by step solution to the largest number (I will give hints only for largest number, but the solution for both are the same)

1.Define an int array that is x amounts large
 1.1. Put values in the array 
DONE
 
2.Define an int variable called maxNumber, this is where we store the value of largest number
 2.1. The value of maxNumber should be the first value of the array
 Done
 
3.Go through the array with a loop
 3.1. If the i number is bigger than the maxNumber, we need to change the value of maxNumber to i
 3.2. Repeat  3.1. on the next cycle until the end of the array
Print out - "Largest number of array is " + maxNumber 


*/


public class Main {
  public static void main(String[] args) {

    int[] numbers = new int[5];
    numbers[0] = 1;
    numbers[1] = 7;
    numbers[2] = 3;
    numbers[3] = -2;
    numbers[4] = 100;

    int maxNumber = numbers[0]; // 1 > 1 ... 7 > 1 ... 3 > 7 .... ... 100 > 7
    //1st cycle -> maxNumber is 1
    //2nd cycle -> maxNumber is 7
    //3rd cycle -> maxNumber is 7
    //...
    //5th cycle -> maxNumber is 100
    //             5 < 5
    for(int i = 0; i < numbers.length; i++) { // 0 1 2 3 4 ... 5
      //The start of the cycle
      if (numbers[i] > maxNumber) {
        maxNumber = numbers[i];
      }

      System.out.println("Oskars");
      //The end of the cycle
    }

    
    System.out.println("Largest number of array is " + maxNumber);
  }
}

/*

We have an array with different numbers {1, 3, 4, 2, 5, 8}

User is providing a number

Check whether or not this number exists in the array
*/

import java.util.Scanner;

public class Main {
  public static void main(String[] args) {

    int[] numbers = { 1, 3, 4, 2, 5, 8 }; // numbers.length = size of the numbers = 6

    System.out.println("Please write your favourite digit");

    Scanner scanner = new Scanner(System.in);
    int favouriteNumber = scanner.nextInt();

    boolean isFound = false;
    
    for (int i = 0; i < numbers.length; i++) {

      if (numbers[i] == favouriteNumber) {
        isFound = true;
        break; //EXITS THE FOR LOOP ALTOGETHER, ignoring the i < numbers.length
      }
      
    }
    if(isFound){
      System.out.println("Your favourite number " + favouriteNumber + " is in the array");
    } else {
      System.out.println("Your favourite number " + favouriteNumber + " is NOT FOUND!");
    }
    
    scanner.close();
  }
}

/*

We have an array with different numbers {1, 3, 4, 2, 5, 8}

User is providing a number

Check whether or not this number exists in the array

1. Define an array with numbers
2. Ask the user for a favouriteNumber
3. Defining a isFound boolean (represents whether or not the number is found)
4. Go through the array with a for loop
4.1. On every cycle we check whether or not the number is equal to the favouriteNumber
4.1.1. If it is, we set isFound to true and exit the searching loop with a "break;"
4.1.2. If it is not, we set isFound to false and we repeat the 4.1. steps 
5. At the end of the cycle we check whether or not isFound is true
5.1. If isFound == true -> Then we print your favourite number is found
5.2. If isFound == false -> Then we print NOT FOUND!

*/

import java.util.Scanner;

public class Main {
  public static void main(String[] args) {

    int[] numbers = { 1, 3, 4, 2, 5, 8, 1000 }; // numbers.length = size of the numbers = 6

    System.out.println("Please write your favourite digit");

    Scanner scanner = new Scanner(System.in);
    int favouriteNumber = scanner.nextInt(); // 2

    boolean isFound = false; // default value is that it is not found
    
    for (int i = 0; i < numbers.length; i++) { // GO through every index in the array
          //       2 == 2
      if (numbers[i] == favouriteNumber) { // if the number is equal to the favouriteNumber
        isFound = true;
        break; //EXITS THE FOR LOOP ALTOGETHER, ignoring the i < numbers.length
      } // If the number is not equal -> move on to the next cycle
      
    }
    
    if(isFound == true){
      System.out.println("Your favourite number " + favouriteNumber + " is in the array!");
    } else {
      System.out.println("Your favourite number " + favouriteNumber + " is NOT FOUND!");
    }
    
    scanner.close();
  }
```



   
