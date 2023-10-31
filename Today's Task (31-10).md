## Today mandatory task :


* Write a Python program that asks the user for their age and prints "You are an adult" if the age is 18 or older, otherwise prints "You are a minor'.


```python
x=int(input('enter age'))

if x <=0:
    print('enter correct age') ##-->print statement execute only when the above if statement is satisfied
elif x>=18:
    print('you are an adult') 
else:
    print('you are minor')
```

    enter age20
    you are an adult
    

* Write a program that takes a numerical grade (out of 100) as input and prints the corresponding letter grade according to the following scale:
 90-100: A
 80-89: B
 70-79: C
 60-69: D
 Below 60: F



```python
x=int(input('enter number'))

if x >100:
    print('enter number (out 100)')
elif x>=90:
    print('A')
elif x>=80:
    print('B')
elif x>=70:
    print('C')
elif x>=60:
    print('D')
else:
    print(f)

```

    enter number69
    D
    

* Write a program that calculates the Body Mass Index (BMI) of a person. The user should input their weight in kilograms and height in meters. The program should then print whether the person is underweight, normal weight, overweight, or obese


```python
x=int(input('your weight in kg'))
y=int(input('your height in cm'))
z=x/ y*y
format=print(f'the BMI of a person whose x and y are {x}and{y}respectively is{z}')
if z<18.5:
    print('underweight')
elif z>=18.5: 
    print('normal weight')
elif z==25 and z<=29.9:
    print('over weight')
else:
    print('obesity')


```

    your weight in kg45
    your height in cm5
    the BMI of a person whose x and y are 45and5respectively is45.0
    normal weight
    

* Write a program that asks the user for three numbers and prints the maximum of the three.


```python
x=int(input('enter first number'))
y=int(input('enter second number'))
z=int(input('enter third number'))
if x>y and x>z:
    print('first number is highest',(x))
elif y>x and y>z:
    print('Second NUmber is heighest',(y))
else:
    print('Third number is Heighest',(z))

```

    enter first number2
    enter second number3
    enter third number5
    Third number is Heighest 5
    

* Write a program that asks the user for a temperature (in Celsius) and prints "It's freezing" if the temperature is below 0, "It's cool" if it's between 0 and 10, "It's warm" if it's between 10 and 20, and "It's hot" if it's above 20


```python
c=float(input('enter temperature in celsius  '))
y=(c* 1.8) + 32
if y>0 and y<0:
    print('its freezing')
elif y in range(0,10):
    print('its cooling')
elif y in range(10,20):
    print('its Warm')
else:
    print('its hot')
          
```

    enter temperature in celsius  45
    its hot
    

* Write a program that asks the user for a number (1-7) and prints the corresponding day of the week.



```python
D=int(input('enter Number '))
if D >=7 and D<=1:
    print('enter valid number')
elif D==1:
    print('SUNDAY')
elif D==2:
    print('MONDAY')
elif D==3:
    print('TUESDAY')
elif D==4:
    print('WEDNESDAY')
elif D==5:
    print('THURSDAY')
elif D==6:
    print('FRIDAY')
else:
    print('SATURDAY')
```

    enter Number 1
    SUNDAY
    

* Write a program that asks the user for a number and prints "In range" if the number is between 10 and 20 (inclusive), and "Out of range" otherwise.



```python
x=int(input('enter a number   '))

if x in range(9,21):
    print('the given number is inclusive')
else:
    print('out of range')
```

    enter a number   10
    the given number is inclusive
    

* Write a program that asks the user for an integer and prints whether it's even or odd.


```python
x=int(input('enter the number   '))

if x%2==0:
    print('the given number is a   ' 'EVEN')
else:
    print('the given number is'   'ODD')
          
```

    enter the number   2
    the given number is a   EVEN
    


* Write a Python program to add 'ing' at the end of a given string (string length should be equal to or more than 3). If the given string already ends with 'ing' then add 'ly' instead.If the string length of the given string is less than 3, leave it unchanged



```python
y=input('enter a string  ')

if len(y)==2:
    print((y))
elif y.endswith('ing'):
    print((y).replace('ing','ly'))
else:
    print((y)+('ing'))

```

    enter a string  string
    strly
    




```python

```
