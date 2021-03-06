# Laboratory 5 - OOP

## Inheritance

##### Task1

1. Create 10 classes with their names as first 10 aphabetical letters (A, B, C, D, ... , J).

Each next class inherits from previous letter class (ex: `B inherits from A, C inherits from B ...`).

Each class should have their own String property with corresponding letter as their refference (ex: `A - public String a; public B - String b; ... J - public String j;`).

2. Create by an object of each class type and print it in console in a clever way (such that to be clear each objects states).

##### Task 2 

1. Change all states from previous classes from public access specifiers to protected.

2. Create class X which has a private String name property that should have also a constructor for that X.

3. Add a object of X to A class as a state and modify the constructor of A from `A(new String("blabla"))` to `A(new String("blabla"), new X("some name"))`.

Checkout for errors if appeared in child classes and try to resolve the issue.

`hint: use super("blabla", x) in Java, base("blabla", x) in C# and SuperClassName("blabla", x) in C++, where x is a instance of type X`.

4. Finally print J and see what happens states does it have.

##### Task3 

1. Add initial value to state X from class A. (ex: `protected X x = new X("xxx")`).

Print a object of J and see the result.

2. Go in class D and create also a state with the same name `x` as in class A and give another initial value.

Print the result and checkout if any changes.

3. Now do the same in class H and add to a state x another initial value.

Chackout again if any changes when printing object of class J.

4. Make the property `x` from class `H` private and checkout now if any errors appeared and try to solve them.

`hint: property x is not visible any more in child classes cause of private modifier in most near by hierarchy class containing this state.`
