# OOPS-in-java

## Table of Comtents
* Data-Hiding
* Abstraction
* Encapsulation
* Tightly Encapsulated class
* IS-A Relationship
* Has-A Relationship
* Method Signature
* Overloading 
* Overriding
* Static Control Flow
* Instance Control Flow
* Constructors
* Coupling
* Cohesion
* Type Casting
>
>
>
### Data Hiding
Outside person can't access our internal data directly or our internal data should not go out directly.This OOP feature is nothing but data hiding.
After validation or identification outisde person can access internal data
Ex 1: After providing proper username and password we can able to access gmail inbox information.
Ex 2: Even though we are valid customers of the bank our account information but we can't access other account information.

By declaring data member(variable) as private we can achieve data hiding

![image](https://user-images.githubusercontent.com/67812755/116021747-6b2e3f00-a666-11eb-9418-35647f711d4f.png)

The main advantage of data-hiding is Security 
Note: It is highly recommed data member(variable) as private

### Abstraction
Hiding internal implementation and just highlight want we are offering is the concept of abstraction.
Ex: Though Bank ATM GUI Screen bank people are highlighting what services they are offering without highligting internal implementation.

The main advantages of abstraction are 
> We can achieve Security because we are not highlighting our internal implementation.
> 
> Without affecting outside person we can perform any changes and hence enhancement will become easy.
> 
> It will improve maintainabilty of the application.
> 
> It improves easiness to use our system.
> 

#### Implemenation
By using inteface and abtract classes we can implement abstraction


### Encapsulation
The process of biding data and corresponding method into a single unit is nothing but encapsulation 

![2](https://user-images.githubusercontent.com/67812755/116024094-1a6d1500-a66b-11eb-9e1d-04cc3778a187.png)

If any components follows data hiding and abstraction such type of componenet is said to be encapsulated components


**Encapsulation= Data hiding + Abstraction**



![image](https://user-images.githubusercontent.com/67812755/116027644-0d542400-a673-11eb-9e4c-a8ae893744cc.png)

The main advantages of encapsulation are 
> Security
> 
> Enchacement will be improved
>
> It improves mainabilty of the application
> 

The main advantages of Encapulation is we can achieve Securty but the main Disadvanatges of Encapsulation is It increases length of the code and slow down Execution

### Tightly Encapsulated Class
A class is said to be tighly encapsulated if and only if each and every variable declared as private whether class conatins corresponding getter and setter method are not and whether these methods are declared as public or not these things we are required to check

![2 (2)](https://user-images.githubusercontent.com/67812755/116028501-e7c81a00-a674-11eb-92e0-5e8c10828a77.png)

**Which of the following class are tighly encapsulated?**

Example !:

![2 (3)](https://user-images.githubusercontent.com/67812755/116029122-3924d900-a676-11eb-909d-e01369dd9750.png)

Class A and C are tighly encapsulated

Example 2:

![2 (5)](https://user-images.githubusercontent.com/67812755/116029314-acc6e600-a676-11eb-8e4c-b135c8a228f1.png)



No class are tighly encapsulated
