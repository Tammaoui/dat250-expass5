- [x] Experiment 1: Getting started
- [x] Experiment 2: Spring Boot
- [x] Experiment 3: REST service
- [x] Experiment 4: Data Access

## Technical problems
The main problems I encountered were depenencies that weren't added correctly. This was mainly my fault because I didn't add Spring Web to begin with.
I also had a issue where I got a different result by running with Intellij compared to ./mvnw spring-boot:run
I kept getting this error message:

`Description:
Parameter 0 of method demo in com.example.dat250exercise5.Application required a bean of type 'com.example.dat250exercise5.ex4.CustomerRepository' that could not be found.
Action:
Consider defining a bean of type 'com.example.dat250exercise5.ex4.CustomerRepository' in your configuration.`

This was solved by entering the command in the terminal instead.

## Link to code
Link: https://github.com/Tammaoui/dat250-expass5-code
