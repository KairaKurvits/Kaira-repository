# Welcome to Kaira's repository ❤💖

## I am curretly studying new programming languages 💪🤞
1. Java
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

```

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
```
3. Python

   
