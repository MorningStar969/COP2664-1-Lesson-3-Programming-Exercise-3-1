# COP2664-1-Lesson-3-Programming-Exercise-3-1
This is a GitHub repository link for Programming Exercise 3-1 of Lesson 3

// This program is used to determine the amount a driver has to pay for a speeding ticket depending on the speed they were going and the speed limit.

import Foundation // Imports the Foundation library
var speedLimit = 50 // Sets the speed limit to 50
var drivingSpeed = 60 // Sets the driving speed to 60
if drivingSpeed <= speedLimit { // If the driving speed is less than or equal to the speed limit, then the program will print that the driver was not speeding.
  print("No ticket")
} else if drivingSpeed <= 20 { // If the driving speed is less than or equal to 20, then the program will print that the driver was speeding and that they will be fined $100.
  print("Ticket: $75") 
} else if drivingSpeed <= 40 { // If the driving speed is less than or equal to 40, then the program will print that the driver was speeding and that they will be fined $200.
  print("Ticket: $150")
} else { // If the driving speed is greater than 40, then the program will print that the driver was speeding and that they will be fined $300.
  print("Ticket: $300")
}
