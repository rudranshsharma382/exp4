Experiment 4: Study of Sets in Python
Student Details

Name: Rudransh Sharma

PRN: 25070123096

Experiment No.: 4

Aim

The aim of this experiment is to study the Set data type in Python, understand its properties, and perform various set operations such as creation, insertion, deletion, union, intersection, difference, symmetric difference, and the use of frozenset. The experiment also demonstrates real-life applications of sets like removing duplicates, finding common elements, and managing groups.

Theory

A set in Python is an unordered collection of unique elements. Sets are defined using curly braces {} or the set() constructor. Since sets are unordered, they do not support indexing or slicing. Duplicate elements are automatically removed.

Key Characteristics of Sets

Unordered collection

Does not allow duplicate values

Mutable (elements can be added or removed)

Does not support indexing

Can store multiple data types

Frozen Set

A frozenset is an immutable version of a set. Once created, elements cannot be added or removed. It is useful when a fixed collection of unique elements is required.

Algorithms
Algorithm 1: Creation and Accessing Elements of a Set

Create a set with multiple elements.

Print the set.

Try to access an element using an index.

Observe the error as sets do not support indexing.

Algorithm 2: Set with Multiple Data Types and Duplicate Removal

Create a set containing integers, floats, strings, and boolean values.

Print the set.

Observe that duplicate values are automatically removed.

Algorithm 3: Adding and Removing Elements from a Set

Create a set with string elements.

Use add() to insert a new element.

Use remove() to delete an existing element.

Print the updated set.

Algorithm 4: Set Operations (Union, Intersection, Difference)

Create two sets with numeric values.

Perform union using union() and | operator.

Perform intersection using & operator.

Find difference using - operator.

Find symmetric difference using ^ operator.

Print all results.

Algorithm 5: Working with Frozenset

Create a frozenset with string elements.

Print the frozenset.

Try to add a new element using add().

Observe the error since frozenset is immutable.

Algorithm 6: Removing Duplicate Students Using Set

Create a list of student names with duplicate entries.

Convert the list into a set.

Print the original list and the set of unique students.

Algorithm 7: Finding Common Subjects Among Students

Create sets of subjects chosen by different students.

Use intersection operator & to find common subjects.

Display the result.

Algorithm 8: Club Membership Analysis

Create sets of students in cricket and football clubs.

Find students in both clubs using intersection.

Find students in only one club using symmetric difference.

Display the results.

Algorithm 9: Finding Absent Students

Create a set of all students.

Create a set of present students.

Subtract present students from all students.

Display the absent students.

Algorithm 10: Removing Discontinued Course

Create a set of course codes.

Identify the discontinued course.

Remove it using discard() method.

Print the updated course codes.

Definition of Commands Used

set(): Creates a new set.

frozenset(): Creates an immutable set.

add(): Adds an element to a set.

remove(): Removes a specified element from a set (raises error if not found).

discard(): Removes an element if present (no error if absent).

union() / |: Returns a set containing all elements from both sets.

intersection() / &: Returns common elements between sets.

difference() / -: Returns elements present in one set but not in another.

symmetric difference() / ^: Returns elements present in only one of the sets.

print(): Displays output on the screen.

Conclusion

In this experiment, we successfully studied the Set data type in Python and performed various operations on it. We observed that sets automatically remove duplicate values and do not support indexing. The experiment also demonstrated practical applications of sets such as finding unique values, common elements, and differences between groups. The use of frozenset showed how immutability can be enforced in Python. Thus, sets are highly useful for mathematical operations and data analysis tasks.
