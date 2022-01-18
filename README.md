# ios1

import UIKit
import Foundation

var greeting = "Hello, playground"
print("Hi",10,12.25)//comma whenever used it will give space  in the output

//string interpolation
//string interpolation is done using forward slash'\' in the quotes with in the parenthesis ()
var name = "poorna chand"
print ("hello, \(name)")

var grade = "82.5"
print ("Hello, \(name) your grade is \(grade)")
var proLan = "Swift";
print ("I like the \(proLan) programming language")

var age = 24

print ("your age is, \(age) years old in another \(age) you will be \(age * 2) years")

// use """ to print multiple lines

print("""
      jshbf
      sfsr
      saavvr
""")


// \r is a carrier return

print("Welcome to Swift Programming")
print("Fall 2021")
print("*************")

// terminator is to print on the same line
print("Welcome to Swift Programming" , terminator : "-" )
print("Fall 2021")

print("The list of numbers are ", terminator: "---")
print(1,2,3,4,5,6)
print("The new pattern is", terminator : "___")
// seperator is used to print on same line using the given symbol
print(1,2,3,4,5,6, separator: "*")


//worksheet 2 constant, variables and tupples

let pi = 3.14

print ("pi value is ", terminator: ": ")
print ("\(pi * 2)")

// tupples
var lname = "poornachand"
var fname = "yanamadala"
(lname , fname ) = (fname , lname)
print ("my surname/initial is \(lname),and my name is \(fname)")

let flowers = ("tulips","roses", (12.0,23.2) )
print("\(flowers.0)")
print(flowers.1)
print ("price of the \(flowers.0) is \(flowers.2.0)", terminator: " $ " )
print ("price of the \(flowers.0) is \(flowers.2.1)")
print(type(of: flowers))

