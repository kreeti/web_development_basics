## Ruby Exercises

1. Define and explain Class and Object in Ruby.

2. What is the meaning of "open classes" in Ruby.

3. Describe Module in Ruby.

4. How to implement multiple inheritance in Ruby?

5. Describe about Block, Proc, and Lambda in Ruby.

6. Describe the different types of access specifiers in Ruby.

7. What’ll be the result of this following codes.
```
def test
   yield 5
   puts "You are in the method test"
   yield 100
end

test {|i| puts "You are in the block #{i}"}
```

8. Write a program that takes a number n and outputs a point-down triangle of height n and width 2n-1; the output for n = 6 would be:

```
Enter a number: 6

***********
 *********
  *******
   *****
    ***
     *
```

9. fred = [ 4, 9, 18, 3, 87, 9, 12 ]
Compute a new array with each member of fred doubled in a single line using map.

10. alex = [ 'Susan', 'Joe', 'Alex', 'Alice', 'Sam' ]
Print the lengths of the members of alex that start with A or end with e, in oneline.

11. Given a zero index array find the sum of contiguous subarray which has the largest sum.
Time-complexity should be: O(n)
Auxiliary space should be: O(1)
Note: returns zero if all numbers are negative.

12. Given a zero index array find the sum of contiguous subarray which has the largest sum.
Time-complexity should be: O(n)
Auxiliary space should be: O(1)
Note: should accept all negative numbers.

13. Given a number “n”,count the number of set bits in it.

14. Use the select method to extract all odd numbers from an array and store into a new array.

15. Given the following data structures. Write a program that moves the information from the array into the empty hash that applies to the correct person.
contact_data = [["Joe Smith", "joe@email.com", "123 Main st.", "555-123-4567"],
            ["Sally Johnson", "sally@email.com", "404 Not Found Dr.", "123-234-3454"]]

contacts = {"Joe Smith" => {}, "Sally Johnson" => {}}

16. Consider the following employee xml, parse it and store Name of each employee in an array using ruby.
```
<Personnel>
<Employee type="permanent">
<Name>Seagull</Name>
<Id>3674</Id>
<Age>34</Age>
</Employee>
<Employee type="contract">
<Name>Robin</Name>
<Id>3675</Id>
<Age>25</Age>
</Employee>
<Employee type="permanent">
<Name>Crow</Name>
<Id>3676</Id>
<Age>28</Age>
</Employee>
</Personnel>
```
17. Consider the following employee json and write the following programs.
    * parse that json and store phoneNumber of each employee in an array using ruby.
    * parse that json and create emp.csv file where only employeeName (firstName + lastName), phoneNumber and emailAddress are stored.
    * After creating that emp.csv parse it and store all employeeName in an array who has gmail account.
```
{
	"Employees": [{
		"userId": "rirani",
		"jobTitleName": "Developer",
		"firstName": "Romin",
		"lastName": "Irani",
		"preferredFullName": "Romin Irani",
		"employeeCode": "E1",
		"region": "CA",
		"phoneNumber": "408-1234567",
		"emailAddress": "romin.k.irani@gmail.com"
	}, {
		"userId": "nirani",
		"jobTitleName": "Developer",
		"firstName": "Neil",
		"lastName": "Irani",
		"preferredFullName": "Neil Irani",
		"employeeCode": "E2",
		"region": "CA",
		"phoneNumber": "408-1111111",
		"emailAddress": "neilrirani@gmail.com"
	}, {
		"userId": "thanks",
		"jobTitleName": "Program Directory",
		"firstName": "Tom",
		"lastName": "Hanks",
		"preferredFullName": "Tom Hanks",
		"employeeCode": "E3",
		"region": "CA",
		"phoneNumber": "408-2222222",
		"emailAddress": "tomhanks@gmail.com"
	}]```

18. Fetch JSON from https://api.github.com/repos/rails/rails/commits and do the followings
    * parse it and create an array of all unique authors.
    * parse it to show last five commiters.
