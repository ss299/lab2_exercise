# lab2_exercise

Exercise 2: indexing and filtering vectors

# lab2_exercise

#Exercise 2: indexing and filtering vectors

#Create a vector `first_ten` that has the values 10 through 20 in it (using 
#                                                                     the : operator)

first_ten <- 10:20


#Create a vector `next_ten` that has the values 21 through 30 in it (using the seq() function)
next_ten <- seq(21,30)


#Create a vector `all_numbers` by combining the previous two vectors

all_numbers <- c(first_ten, next_ten)

#Create a variable `eleventh` that contains the 11th element in `all_numbers`

eleventh <- all_numbers[c(11)]


#Create a vector `some_numbers` that contains the 2nd through the 5th elements of `all_numbers`
some_numbers <- all_numbers[c(2:5)]

#Create a vector `even` that holds the even numbers from 1 to 100

num <- 1:100
num %% 2 == 0
even <-



