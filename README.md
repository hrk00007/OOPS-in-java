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
Note: It is highly recommended data member(variable) as private

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


## IS-A Relationship

It's also known as inheritance. The main advantage of IS-A-Relationship is code resuability by using extends keyword we cam implement Is-A-Relationship.


![Blank diagram (7)](https://user-images.githubusercontent.com/67812755/116337855-6d280780-a7f8-11eb-80a3-499ab2aba3f1.png)


**Conclusion**

1. Whathever method parents has by default available to the child and hence child reference we can call both parent and child class methods.

2. Whathever method child has not availae to the parent and hence parents reference we can't class child specific method.

3. Parents reference can be used to hold child object but by using that refernce we can't class child specific method. But we can call the method present in Parent class.

4. Parent reference can be used to hold child object but child refernce can't be used to hold parent object 


**With and Without Inheritance**

![Encapsulation](https://user-images.githubusercontent.com/67812755/116339307-d27cf800-a7fa-11eb-903a-6cf76a597da3.png)

Total JAVA API is implemented based on inheritance concept. The most common method which are applicable for any java object are defined in object class. And hence every class in java is a child class of object either directly or indirectly so that object class method by default to every java class without rewriting due to this object class root for all java classes.
Throwable defines the most common method which are required for every expection on error classes hence this class has root for java Exception hierarchy.

