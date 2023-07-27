# Programming_Languages
This srepository contains training assets for the following programming languages: ruby, Groovy, Python, Perl, Shell and PowerShell

 Learning coding with fundamental concepts is a great way to start your programming journey. Here are some core concepts along with examples of the programming languages you mentioned(ruby, Groovy, Python, Perl, Shell and PowerShell):

## 1. Variables:
Variables are used to store data in a program. They have a name and a value associated with them. You can use variables to store data, such as numbers, strings, or other variables.

- ### Ruby:
<code_start>
age = 25
name = "John"
<code_end>

- ### Groovy:
<code_start>
def age = 25
def name = "John"
<code_end>

- ### Python:
<code_start>
age = 25
name = "John"
<code_end>

- ### Perl:
<code_start>
my $age = 25;
my $name = "John";
<code_end>

- ### Shell
<code_start>
age=25
name="John"
<code_end>

- ###  powershell
<code_start>
$age = 25
$name = "John"
<code_end>

## 2. Data Types And operators:

Programming languages have different data types to represent different kinds of values. Such as integers, floating-point numbers, characters, strings, booleans, and objects. Knowing the data types available in a language and how to use them is important for writing effective code.

### Ruby:

<code_start>
number = 42    # Integer
name = "Alice"        # String
is_true = true        # Boolean
price = 3.14          # Float
<code_end>

### Groovy:

<code_start>
def number = 42       // Integer
def name = "Alice"    // String
def is_true = true    // Boolean
def price = 3.14      // Float
<code_end>

###  Python
<code_start>
number = 42          # Integer
name = "Alice"       # String
is_true = True       # Boolean
price = 3.14         # Float
<code_end>
### Perl
<code_start>
my $number = 42;     # Integer
my $name = "Alice";  # String
my $is_true = 1;     # Boolean (1 is true, 0 is false)
my $price = 3.14;    # Float
<code_end>
### Shell
<code_start>
number=42           # Integer
name="Alice"        # String
is_true=true        # Boolean (Note: No native boolean in shell, using 0/1)
price=3.14          # Float
<code_end>
### PowerShell
<code_start>
$number = 42        # Integer
$name = "Alice"     # String
$is_true = $true    # Boolean
$price = 3.14       # Float
<code_end>

- ### Operators: 

Operators are symbols that perform operations on variables and expressions. Some common operators include arithmetic operators (+, -, *, /), comparison operators (==, ==, !=, <, >, <= , >=), and assignment operators (=).

## 3. Control Flow:

Control flow structures allow you to control the execution of your code based on conditions.Some common control structures include if-else statements, for loops, while loops, and do-while loops.

- ### Ruby:

<code_start>
if age >= 18
  puts "You are an adult."
else
  puts "You are a minor."
end
<code_end>

- Loop example
<code_start>
5.times do |i|
  puts "Iteration #{i+1}"
end
<code_end>

- ### Groovy:

<code_start>
if (age >= 18) {
  println("You are an adult.")
} else {
  println("You are a minor.")
}
<code_end>

- Loop example

<code_start>
5.times { i ->
  println("Iteration ${i+1}")
}
<code_end>

- ### Python:

<code_start>
if age >= 18:
    print("You are an adult.")
else:
    print("You are a minor.")
<code_end>

- Loop example

<code_start>
for i in range(1, 6):
    print(f"Iteration {i}")
<code_end>

- ### Perl:

<code_start>

if ($age >= 18) {
    print "You are an adult.\n";
} else {
    print "You are a minor.\n";
}

<code_end>

- Loop example

<code_start>
for my $i (1..5) {
    print "Iteration $i\n";
}
<code_end>

- ### Shell:

<code_start>
if [ "$age" -ge 18 ]; then
    echo "You are an adult."
else
    echo "You are a minor."
fi
<code_end>

- Loop example

<code_start>
for ((i=1; i<=5; i++)); do
    echo "Iteration $i"
done
<code_end>

- ### PowerShell:

<code_start>
if ($age -ge 18) {
    Write-Host "You are an adult."
} else {
    Write-Host "You are a minor."
}
<code_end>

- Loop example

<code_start>
1..5 | ForEach-Object {
    Write-Host "Iteration $_"
}
<code_end>


## 4. Functions:
Functions are blocks of reusable code that perform a specific task.

- ### Ruby:

<code_start>
def greet(name)
  puts "Hello, #{name}!"
end

greet("Alice")

<code_end>

- ### Groovy:

<code_start>
def greet(name) {
  println("Hello, $name!")
}

greet("Alice")
<code_end>

- ### Python:


<code_start>
def greet(name):
    print(f"Hello, {name}!")

greet("Alice")
<code_end>

- ### Perl:

<code_start>

sub greet {
    my ($name) = @_;
    print "Hello, $name!\n";
}

greet("Alice");
<code_end>

- ### Shell:

<code_start>
greet() {
    echo "Hello, $1!"
}

greet "Alice"
<code_end>

- ### PowerShell:


<code_start>
function greet($name) {
    Write-Host "Hello, $name!"
}

greet "Alice"
<code_end>

## 5. Arrays:
Arrays are data structures that store multiple values in an ordered sequence.

- ### Ruby
<code_start>
numbers = [1, 2, 3, 4, 5]
<code_end>
- ### Groovy
<code_start>
def numbers = [1, 2, 3, 4, 5]
<code_end>
- ### Python
<code_start>
numbers = [1, 2, 3, 4, 5]
<code_end>
- ### Perl
<code_start>
my @numbers = (1, 2, 3, 4, 5);
<code_end>
- ### Shell
<code_start>
numbers=(1 2 3 4 5)
<code_end>
- ### PowerShell
<code_start>
$numbers = 1, 2, 3, 4, 5
<code_end>

## 6. Loops:
Loops allow you to repeatedly execute a block of code based on a condition.

- ###  Ruby
<code_start>
5.times do |i|
  puts "Iteration #{i+1}"
end
<code_end>
- ###  Groovy
<code_start>
5.times { i ->
  println("Iteration ${i+1}")
}
<code_end>
- ### Python
<code_start>
for i in range(1, 6):
    print(f"Iteration {i}")
<code_end>
- ### Perl
<code_start>
for my $i (1..5) {
    print "Iteration $i\n";
}
<code_end>
- ### Shell
<code_start>
for ((i=1; i<=5; i++)); do
    echo "Iteration $i"
done
<code_end>
- ### PowerShell
<code_start>
1..5 | ForEach-Object {
    Write-Host "Iteration $_"
}
<code_end>

## 7. OOP:

Object-Oriented Programming (OOP) is a programming paradigm that revolves around the concept of "objects." An object is a self-contained unit that combines data (attributes or properties) and behavior (methods or functions) that operate on that data. OOP allows you to model real-world entities, abstract concepts, and interactions between different entities in a more intuitive and organized manner.

Let's explore the OOP concepts and syntax for each of the languages you mentioned: Ruby, Groovy, Python, Perl, Shell, and PowerShell.

### 1. Classes and Objects:
A class is a blueprint or template for creating objects, defining their attributes, and specifying their behaviors. Objects are instances of classes.
- ### Ruby
<code_start>
class Person
  attr_accessor :name, :age
  
  def initialize(name, age)
    @name = name
    @age = age
  end
  
  def greet
    puts "Hello, my name is #{@name} and I am #{@age} years old."
  end
end



#Creating an object of the class
person = Person.new("Alice", 30)
person.greet


<code_end>

- ### Groovy
<code_start>
class Person {
  String name
  int age
  
  Person(String name, int age) {
    this.name = name
    this.age = age
  }
  
  void greet() {
    println "Hello, my name is $name and I am $age years old."
  }
}

// Creating an object of the class
Person person = new Person("Alice", 30)
person.greet()
<code_end>

- ### Python
<code_start>
class Person:
    def __init__(self, name, age):
        self.name = name
        self.age = age
        
    def greet(self):
        print(f"Hello, my name is {self.name} and I am {self.age} years old.")

#Creating an object of the class
person = Person("Alice", 30)
person.greet()
<code_end>

- ### Perl:
Perl is not natively object-oriented, but you can use modules like Moose or Moo to implement OOP in Perl. Here's an example using Moose:


-Perl with Moose module
<code_start>
use Moose;

#Define class
class Person {
  has 'name' => (is => 'rw', isa => 'Str');
  has 'age' => (is => 'rw', isa => 'Int');
  
  sub greet {
    my ($self) = @_;
    print "Hello, my name is $self->{name} and I am $self->{age} years old.\n";
  }
}


#Creating an object of the class
my $person = Person->new(name => "Alice", age => 30);
$person->greet();

<code_end>


### 2. Inheritance:
Inheritance allows one class to inherit attributes and methods from another class, creating a hierarchy of classes.

- ###  Ruby

<code_start>
class Animal
  def speak
    puts "Animal speaks."
  end
end

class Dog < Animal
  def speak
    puts "Woof!"
  end
end

dog = Dog.new
dog.speak
<code_end>

- ### Groovy

<code_start>
class Animal {
  void speak() {
    println "Animal speaks."
  }
}

class Dog extends Animal {
  void speak() {
    println "Woof!"
  }
}

def dog = new Dog()
dog.speak()
<code_end>

- ### Python
<code_start>
class Animal:
    def speak(self):
        print("Animal speaks.")

class Dog(Animal):
    def speak(self):
        print("Woof!")

dog = Dog()
dog.speak()

<code_end>

- ### Perl with Moose module
<code_start>
use Moose;

class Animal {
  sub speak {
    print "Animal speaks.\n";
  }
}

class Dog extends Animal {
  sub speak {
    print "Woof!\n";
  }
}

my $dog = Dog->new();
$dog->speak();

<code_end>

## 3. Encapsulation:
Encapsulation restricts direct access to the internal state of an object and provides access through methods.

- ### Ruby
<code_start>
class Person
  def initialize(name, age)
    @name = name
    @age = age
  end
  
  def name
    @name
  end
  
  def age
    @age
  end
  
  def greet
    puts "Hello, my name is #{name} and I am #{age} years old."
  end
end

person = Person.new("Alice", 30)
person.greet

<code_end>

- ### Groovy
<code_start>
class Person {
  private String name
  private int age
  
  Person(String name, int age) {
    this.name = name
    this.age = age
  }
  
  String getName() {
    name
  }
  
  int getAge() {
    age
  }
  
  void greet() {
    println "Hello, my name is $name and I am $age years old."
  }
}

def person = new Person("Alice", 30)
person.greet()
<code_end>

- ### Python
<code_start>
class Person:
    def __init__(self, name, age):
        self._name = name
        self._age = age
        
    def get_name(self):
        return self._name
    
    def get_age(self):
        return self._age
    
    def greet(self):
        print(f"Hello, my name is {self.get_name()} and I am {self.get_age()} years old.")

person = Person("Alice", 30)
person.greet()

<code_end>

- ### Perl:
Perl doesn't have native support for private variables. You can use the 'Moose' module for encapsulation as shown in the previous examples.

### 4. Polymorphism:
Polymorphism allows objects of different classes to be treated as objects of the same class, responding to the same method calls.

- ### Ruby

<code_start>
class Animal
  def speak
    puts "Animal speaks."
  end
end

class Dog < Animal
  def speak
    puts "Woof!"
  end
end

def animal_sound(animal)
  animal.speak
end

animal_sound(Animal.new)
animal_sound(Dog.new)
<code_end>

- ### Groovy
<code_start>
class Animal {
  void speak() {
    println "Animal speaks."
  }
}

class Dog extends Animal {
  void speak() {
    println "Woof!"
  }
}

def animalSound(Animal animal) {
  animal.speak()
}

animalSound(new Animal())
animalSound(new Dog())
<code_end>

- ### Python

<code_start>
class Animal:
    def speak(self):
        print("Animal speaks.")

class Dog(Animal):
    def speak(self):
        print("Woof!")

def animal_sound(animal):
    animal.speak()

animal_sound(Animal())
animal_sound(Dog())
<code_end>

- ### Perl with Moose module
<code_start>
use Moose;

class Animal {
  sub speak {
    print "Animal speaks.\n";
  }
}

class Dog extends Animal {
  sub speak {
    print "Woof!\n";
  }
}

sub animal_sound {
  my ($animal) = @_;
  $animal->speak();
}

animal_sound(Animal->new());
animal_sound(Dog->new());
<code_end>


### 5. Abstraction:

Abstraction allows you to hide implementation details and expose only relevant features of an object.
Unfortunately, Perl, Shell, and PowerShell don't have explicit support for abstract classes or interfaces. However, you can use conventions and documentation to achieve the same level of abstraction in your code.

Remember, these examples are meant to give you a basic understanding of OOP concepts and syntax in each language. As you continue learning and practicing OOP, you'll discover more advanced concepts and patterns to make your code more efficient and maintainable. Happy coding!

## 9.File I/O (Input/Output):
It is a fundamental concept in programming, allowing you to read data from files (input) and write data to files (output).

- ###  Ruby:

<code_start>
#Reading from a file
file_path = "sample.txt"
File.open(file_path, "r") do |file|
  puts file.read
end

#Writing to a file
file_path = "output.txt"
File.open(file_path, "w") do |file|
  file.write("Hello, this is written to the file.")
end
<code_end>
- ### File I/O in Groovy:
<code_start>
// Reading from a file
def file = new File("sample.txt")
file.eachLine { line ->
  println line
}

// Writing to a file
def file = new File("output.txt")
file.write("Hello, this is written to the file.")
- ###  File I/O in Python:

<code_end>

<code_start>
#Reading from a file
file_path = "sample.txt"
with open(file_path, "r") as file:
    print(file.read())

#Writing to a file
file_path = "output.txt"
with open(file_path, "w") as file:
    file.write("Hello, this is written to the file.")

<code_end>

- ###  File I/O in Perl:

<code_start>
#Reading from a file
my $file_path = "sample.txt";
open(my $file, '<', $file_path) or die "Cannot open file: $!";
while (my $line = <$file>) {
    print $line;
}
close($file);

#Writing to a file
$file_path = "output.txt";
open($file, '>', $file_path) or die "Cannot open file: $!";
print $file "Hello, this is written to the file.\n";
close($file);
<code_end>
- ###  File I/O in Shell:

<code_start>
#Reading from a file
file_path="sample.txt"
while IFS= read -r line
do
  echo "$line"
done < "$file_path"

#Writing to a file
file_path="output.txt"
echo "Hello, this is written to the file." > "$file_path"

<code_end>

- ###  File I/O in PowerShell:


<code_start>
#Reading from a file
$file_path = "sample.txt"
Get-Content $file_path

#Writing to a file

$file_path = "output.txt"
"Hello, this is written to the file." | Set-Content $file_path
Please note that file I/O operations may require appropriate file permissions, and it's important to handle errors and close files properly after use. The examples provided here are simple and should give you a basic understanding of how to perform file I/O in each language. As you advance in your coding journey, you may encounter more complex scenarios and techniques for file I/O.

<code_end>

## 10.Error Handling:
Error handling is a crucial aspect of programming that allows you to gracefully handle unexpected or exceptional situations that may occur during the execution of a program. Each language has its own way of handling errors and exceptions. Let's explore error handling concepts and provide examples in Ruby, Groovy, Python, Perl, Shell, and PowerShell.

- ###  1. Error Handling in Ruby:
In Ruby, you can use begin, rescue, and ensure blocks for error handling.
<code_start>
#Example with rescue
begin
  num = 10 / 0
rescue ZeroDivisionError => e
  puts "Error: #{e.message}"
end


#Example with ensure (used to ensure execution, regardless of error or not)
begin
  file = File.open("non_existent_file.txt", "r")
  #Perform some operations on the file
rescue Errno::ENOENT => e
  puts "Error: File not found - #{e.message}"
ensure
  file.close if file
end
<code_end>

- ###  2. Error Handling in Groovy:
<code_start>
In Groovy, you can use try-catch blocks for error handling.


//Example with catch
try {
  def num = 10 / 0
} catch (ArithmeticException e) {
  println "Error: ${e.message}"
}

//Example with finally (used to ensure execution, regardless of error or not)
File file = new File("non_existent_file.txt")
try {
  //Perform some operations on the file
} catch (FileNotFoundException e) {
  println "Error: File not found - ${e.message}"
} finally {
  file.close()
}
<code_end>
- ###  3. Error Handling in Python:
<code_start>
In Python, you can use try-except blocks for error handling.


#Example with except
try:
    num = 10 / 0
except ZeroDivisionError as e:
    print(f"Error: {e}")

#Example with finally (used to ensure execution, regardless of error or not)
file = None
try:
    file = open("non_existent_file.txt", "r")
    # Perform some operations on the file
except FileNotFoundError as e:
    print(f"Error: File not found - {e}")
finally:
    if file:
        file.close()

<code_end>

- ###  4. Error Handling in Perl:
In Perl, you can use eval block for error handling.

<code_start>
#Example with eval
eval {
    my $num = 10 / 0;
};
if ($@) {
    print "Error: $@";
}

#Example with finally (used to ensure execution, regardless of error or not)
my $file;
eval {
    open($file, "<", "non_existent_file.txt") or die $!;
    # Perform some operations on the file
};
if ($@) {
    print "Error: File not found - $@";
}
close($file) if $file;
<code_end>
- ###  5. Error Handling in Shell:
In Shell, you can use if statements to check for errors.
<code_start>
#Example with if
if ! command1; then
    echo "Error: command1 failed."
fi

#Example with finally (used to ensure execution, regardless of error or not)
file="non_existent_file.txt"
if [ -e "$file" ]; then
    #Perform some operations on the file
else
    echo "Error: File not found - $file"
fi

- ###  6. Error Handling in PowerShell:
In PowerShell, you can use try, catch, and finally blocks for error handling.
<code_start>
#Example with catch
try {
    $num = 10 / 0
} catch {
    Write-Host "Error: $_"
}

#Example with finally (used to ensure execution, regardless of error or not)
$file = Get-Content "non_existent_file.txt"
try {
    # Perform some operations on the file
} catch {
    Write-Host "Error: File not found - $_"
} finally {
    $file.Dispose()
}
<code_end>

These examples demonstrate the basic error handling concepts in each language. Error handling allows you to handle exceptional situations gracefully and provide meaningful feedback to users or logs for debugging purposes. As you progress in your programming journey, you'll encounter more complex error handling scenarios, and each language has additional features and libraries to handle errors more efficiently.

## 10,Libraries/modules: 
Libraries and modules are collections of pre-written code that provide additional functionality to the programming language. They allow you to extend the language's capabilities and avoid reinventing the wheel. Let's explore the concept of libraries/modules and provide examples in each of the languages you mentioned: Ruby, Groovy, Python, Perl, Shell, and PowerShell.

1. Libraries/Modules in Ruby:
Ruby has a rich ecosystem of libraries called "gems." You can use the require or require_relative statement to load a gem or custom module.

<code_start>
#Using a Gem (Library)
require 'json'
data = '{"name": "Alice", "age": 30}'
parsed_data = JSON.parse(data)
puts parsed_data["name"]

#Using a Custom Module
#custom_module.rb
module MyModule
  def self.greet(name)
    puts "Hello, #{name}!"
  end
end
<code_end>
#main.rb
require_relative 'custom_module'
MyModule.greet("Bob")
2. Libraries/Modules in Groovy:
In Groovy, you can use import to use libraries or custom modules.

<code_start>
// Using a Library
import java.util.Random

Random rand = new Random()
println rand.nextInt(10)

// Using a Custom Module
// customModule.groovy
class MyModule {
  static void greet(String name) {
    println "Hello, $name!"
  }
}

// main.groovy
import customModule.MyModule
<code_end>

MyModule.greet("Alice")
3. Libraries/Modules in Python:
Python has a vast standard library and a package manager called pip to install external libraries.

<code_start>
#Using a Library
import json

data = '{"name": "Alice", "age": 30}'
parsed_data = json.loads(data)
print(parsed_data["name"])

#Using a Custom Module
#custom_module.py
def greet(name):
    print(f"Hello, {name}!")

#main.py
import custom_module
custom_module.greet("Bob")
<code_end>

4. Libraries/Modules in Perl:
In Perl, you can use use to include libraries or custom modules.
<code_start>
#Using a Library
use JSON;

my $data = '{"name": "Alice", "age": 30}';
my $parsed_data = decode_json($data);
print $parsed_data->{'name'};

#Using a Custom Module
#custom_module.pm
package MyModule;

sub greet {
    my ($name) = @_;
    print "Hello, $name!\n";
}

1;

#main.pl
use strict;
use warnings;
use custom_module;

MyModule::greet("Bob");
<code_end>

5. Libraries/Modules in Shell:
In Shell, you can use external programs and scripts as "modules."

<code_start>
#Using an External Program
#Using 'date' command as a library/module
current_date=$(date "+%Y-%m-%d")
echo "Current date: $current_date"

#Using a Custom Script as a Module
#custom_module.sh
#!/bin/bash
function greet() {
    echo "Hello, $1!"
}

#main.sh
#!/bin/bash
source custom_module.sh
greet "Alice"
<code_end>

6. Libraries/Modules in PowerShell:
In PowerShell, you can use cmdlets and modules.

<code_start>
#Using a Built-in Module (Library)
$data = '{"name": "Alice", "age": 30}'
$parsed_data = ConvertFrom-Json $data
Write-Host $parsed_data.name

#Using a Custom Module
#customModule.psm1
function Greet($name) {
    Write-Host "Hello, $name!"
}

#main.ps1
Import-Module ./customModule.psm1
Greet "Bob"
<code_end>

# Resources:
### Ruby: https://www.tutorialspoint.com/ruby/index.htm
### Python: https://docs.python.org/3/tutorial/index.html
### Groovy: https://www.tutorialspoint.com/groovy/index.htm
### Perl : https://www.tutorialspoint.com/perl/index.htm
### Shell:https://www.tutorialspoint.com/unix/shell_scripting.htm
### powershell: https://learn.microsoft.com/en-us/training/modules/script-with-powershell/
