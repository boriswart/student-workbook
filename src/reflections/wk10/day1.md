Read Foundations of C# > C# List and answer the following questions
What is a List in C#?

List is a generic type, so you can create list of any type (it can be reference type such as Customer or value type such as int)

# What List methods seem like you might use them often? Why?


Returns true if the list contains items matching the specified predicate.
checks the predicate and returns a bool.
example .... 
bool result = list.exists(x => x ==3 )
returns a true if one of the elements is equal to 3.

Also:
.FindIndex
// list:	8 3 6 4 2
 int index = list.FindIndex(x => x < 5); 
// index:	1
where returns the first index that meets element i less than 5


and .count  returns the number of elements in the list.



How would you retrieve an item from a list? What method could you use?

forEach:
int retx = null
//:list 8 3 6 2 
for(int x = 0; x< list.count; x++>){
  if (list(x) == 6) {
     retx = x
  }
}
returns index of x where x is equal to 6. Or null if no 6 in the list.  But the nice thing is that a for loop, it  can 
is very flexible. It can be used to compute any value of list(x) so to add all:

int accum = 0
//:list 8 3 6 2 
for(int x = 0; x< list.count; x++>){
     accum += list(x)
}
returns accum  
returns 8 + 3 + 6 + 2  = 19



gregslist cars/houses/jobs 

Instead of moon miner I did console rock paper scissors...  Since this was only a console application I did not push it to github... Pushing it now.

https://github.com/boriswart/cs_rps

