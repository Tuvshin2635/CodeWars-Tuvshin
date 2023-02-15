# CodeWars-Tuvshin

1. Even or Odd

 function evenOrOdd(number) {
  if (number % 2 === 0) {
    return "Even";
    } else {
      return "Odd";
    
  }
};
 
2. Fun with ES6 Classes #1 - People, people, people
class Person {
  constructor(
    firstName = "John",
    lastName = "Doe",
    age = 0,
    gender = "Male"
  ) {
    this.firstName = firstName;
    this.lastName = lastName;
    this.age = age;
    this.gender = gender;
  }

  sayFullName() {
    return this.firstName + " " + this.lastName;
  }

  GreetExtraTerrestrials(raceName) {
    return `Welcome to Planet Earth ${raceName}`;
  }
}
let myPerson1 = new Person();
console.log(myPerson1.sayFullName());

let myPerson = new Person("Martians", "Doe", 0, "Male");
console.log(myPerson.greetExtraTerrestrials(myPerson.firstName));

