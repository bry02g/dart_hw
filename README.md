# dart_hw
You will be modifying the code snippes provided for each question to match the expected output.

You can run your code online [Dart Pad](https://dartpad.dev/)

## Data Types
[Dart Built In Types Docs](https://dart.dev/guides/language/language-tour#built-in-types)
```dart
void main() {
  print(/* add a integer literal here */);
  print(/* add a double literal here */);
  print(/* add a single quote string */);
  print(/* add a double quote string */);
  print(/* add a true boolean literal */);
  print(/* add a true boolean literal */);
  print(/* add a list literal */);
}
/* 
EXPECTED OUTPUT
1
2
abc
abc
true
false
[1, 2, 3, 4, 5]
*/
```

## Variables
[Dart Variable Types](https://dart.dev/guides/language/language-tour#variables)

```dart
void main() {
  //make a variable using var keyword (this infers the type)
  // var name = "Bobby Boy";
  // then print the variable

  // make a explicit variable by using it data type 
  //ex. String name = "Bob";
  // then print the variable

  // make a dynamic variable that is assigned a string literal 
  //(dynamic variables can be reassigned any data type)
  // ex. dynamic name = "Bobby Boi";
  // then print the variable

  // reassigned the dynamic variable to the value 3.5
  // the print the variable

  // try doing the same for the other two
  // YOU SHOULD GET AN ERROR
  //Error: A value of type 'double' can't be assigned to a variable of type 'String'.
  // remove the reassignents

  // Only dynamic variables can be reassigned different data types.
}
/* 
EXPECTED OUTPUT
Bobby Boy
Bob
Bobby Boi
3.5
*/
```

## Operators
[Dart Operators Docs](https://dart.dev/guides/language/language-tour#operators)

```dart
void main() {
    var x = 3;
    var y = 2;

    // NOTE: / (division) operator result is a double
    // NOTE: ~/ (integer division) operator result is a integer
  
    
    print(/* subtract x by y */);
    print(/* add x and y */);
    print(/* divide x by y */);
    print(/* divide x by y(returning an integer result)*/);
    print(/* multiply x by y */);
    print( /* get the remainder of x divided y */);
    print(/* does x equal y */);
    print(/* does x not equal y */);
}
/* 
EXPECTED OUTPUT
1
5
1.5
1
6
1
false
true
*/
```

## Conditionals

[Dart Conditionals Docs](https://dart.dev/guides/language/language-tour#control-flow-statements)

```dart
void main(){
  var x = 3;
  var y = 0;
  
  if(/* check if x is even */){
    print("x is even");
  }
  else{
    print("x is odd");
  }
  
  if(/* check if y is less than zero */){
    print("y is less than zero");
  }
  else if(/* check if y is greater than zero */){
    print("y is greater than zero");
  }
  else{
    print("y is equal to zero");
  }
}

/*
EXPECTED OUTPUT
x is odd
y is equal to zero
*/

```

## Loops
[Dart Loops Docs](https://dart.dev/guides/language/language-tour#for-loops)

```dart
void main(){
  var rows = 5;
  for(/* add code here*/){
    var line = '';
    for(/* add code here */){
      line += '*';
    }
    print(line);
  }

  var nums = [1,2,3,4,5];
  // iterate over the list and print out each element.
  // you can use nums.length to get the size
  // you can access a element by doing nums[index]

  for(/* add code to iterate over nums */){
    print(/* print element*/)
  }
}
/*
EXPECTED OUTPUT
*
**
***
****
*****
1
2
3
4
5
*/
```

## Functions
[Dart Functions Docs](https://dart.dev/guides/language/language-tour#functions)

```dart

bool isEven(int number) {
  return /* is that number even */
}

void greet(name){
    // use String interpolation notation ${name}
    print(/* say Hello, name */);
}

void main(){
  print(isEven(2));
  print(isEven(3));
  
  greet('World');
}

/*
EXPECTED OUTPUT
true
false
Hello, World
*/


```
