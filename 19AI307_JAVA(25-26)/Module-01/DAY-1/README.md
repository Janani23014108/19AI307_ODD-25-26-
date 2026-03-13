# Ex.No:1(A) INTRODUCTION TO JAVA PROGRAMMING, DATA TYPES, VARIABLES AND OPERATORS

## QUESTION:

Lovely is entering a battle arena tournament, but only heroes who meet specific power and skill criteria are allowed inside.

To enter the arena, a hero (Lovely) must satisfy any one of these conditions:

Her power level is above 80 and her rank is above 5
→ (power > 80 && rank > 5)

Or she has a magic orb and her experience is at least 3 years
→ (hasMagicOrb == true && experience >= 3)

Note: If either of the above conditions is satisfied, she is allowed to enter. Otherwise, she is rejected.

Input Format:
First line: int power

Second line: int rank

Third line: boolean hasMagicOrb

Fourth line: int experience

Output Format:

Can Enter Arena: true/false


## AIM:
To write a program to determine whether Lovely can enter the battle arena based on her power level, rank, possession of a magic orb, and experience using logical operators.

## ALGORITHM :
1. Start the program.

2. Input the hero’s details: power, rank, hasMagicOrb, and experience.

3. Check Condition 1: If power > 80 AND rank > 5.

4. Check Condition 2: If hasMagicOrb == true AND experience >= 3.

5. If either Condition 1 OR Condition 2 is true, set canEnter = true, otherwise set canEnter = false.

6. Display the result Can Enter Arena: true/false and Stop the program.



## PROGRAM:
 ```
/*
Program to implement variables and Operators using Java
Developed by: J.JANANI
RegisterNumber:  212223230085

import java.util.*;
class prog
{
    public static void main(String[] args)
    {
        Scanner sc = new Scanner(System.in);
        int power = sc.nextInt();
        int rank = sc.nextInt();
        boolean hasMagicOrb = sc.nextBoolean();
        int experience = sc.nextInt();
        
        System.out.println("Can Enter Arena: "+((power>80 && rank>5)||(hasMagicOrb==true && experience>=3)));
    }
}
*/
```


## OUTPUT:

<img width="723" height="584" alt="image" src="https://github.com/user-attachments/assets/76678fbb-e4f9-48bf-803a-2a23b9aadad5" />


## RESULT:
Thus, the program is executed successfully.

