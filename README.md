# movie_tickets
### _This project is not in a complete or portfolio ready state, and should not be considered representational of professional work._<br><br>
[Epicodus](https://www.epicodus.com/) - Intermediate JavaScript - Week 01 - Lesson 23<br><br>

Initialization Date: 2020-11-03
## Project Description
### _Practice Exercise:_<br>
This project is an exercise in creating objects using constructors and prototypes. Practice adding properties and methods to objects and calling out those properties and methods in the webpage.

## Authors and Contributors
Authored by: Randel Moore, Patrick Osten.

## Contact
RMGit.it@gmail.com

## License

GPLv3

Randel Moore © 2020

## tests

Describe: Movie()

Test:  

Describe: Ticket()

Test: should take user input and create an object with matching properties
Code: function Ticket(movie, time, age, numberOfTickets) {
  this.age = age;
  this.movie = movie;
  this.time = time;
  this.numberOfTickets = numberOfTickets;
}
Expect: input("terminator", "12:00pm", 12, 2).toOutPut(movie1, 2, 1990-5-9, 2) 
