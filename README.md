Experiment 4: Study of Sets in Python
Student Details

Name: Rudransh Sharma

PRN: 25070123096

EXPERIMENT NO.: 4

AIM

The aim of this experiment is to study the Set data type in Python, understand its properties, and perform various set operations such as creation, insertion, deletion, union, intersection, difference, symmetric difference, and the use of frozenset. The experiment also demonstrates real-life applications of sets like removing duplicates, finding common elements, and managing groups.

THEORY

A set in Python is an unordered collection of unique elements. Sets are defined using curly braces {} or the set() constructor. Since sets are unordered, they do not support indexing or slicing. Duplicate elements are automatically removed.

KEY CHARACTERSTICS OF SET

Unordered collection

Does not allow duplicate values

Mutable (elements can be added or removed)

Does not support indexing

Can store multiple data types

FROZEN SET

A frozenset is an immutable version of a set. Once created, elements cannot be added or removed. It is useful when a fixed collection of unique elements is required.

ALGORITHM

ALGORITHM 1: Creation and Accessing Elements of a Set

1.Create a set with multiple elements.

2.Print the set.

3.Try to access an element using an index.

4.Observe the error as sets do not support indexing.

ALGORITHM 2: Set with Multiple Data Types and Duplicate Removal

1.Create a set containing integers, floats, strings, and boolean values.

2.Print the set.

3.Observe that duplicate values are automatically removed.

ALGORITHM 3: Adding and Removing Elements from a Set

1.Create a set with string elements.

2.Use add() to insert a new element.

3.Use remove() to delete an existing element.

4.Print the updated set.

ALGORITHM 4: Set Operations (Union, Intersection, Difference)

1.Create two sets with numeric values.

2.Perform union using union() and | operator.

3.Perform intersection using & operator.

4.Find difference using - operator.

5.Find symmetric difference using ^ operator.

6.Print all results.

ALGORITHM 5: Working with Frozenset

1.Create a frozenset with string elements.

2.Print the frozenset.

3.Try to add a new element using add().

4.Observe the error since frozenset is immutable.

ALGORITHM 6: Removing Duplicate Students Using Set

1.Create a list of student names with duplicate entries.

2.Convert the list into a set.

3.Print the original list and the set of unique students.

ALGORITHM 7: Finding Common Subjects Among Students

1.Create sets of subjects chosen by different students.

2.Use intersection operator & to find common subjects.

3.Display the result.

ALGORITHM 8: Club Membership Analysis

1.Create sets of students in cricket and football clubs.

2.Find students in both clubs using intersection.

3.Find students in only one club using symmetric difference.

4.Display the results.

ALGORITHM 9: Finding Absent Students

1.Create a set of all students.

2.Create a set of present students.

3.Subtract present students from all students.

4.Display the absent students.

ALGORITHM 10: Removing Discontinued Course

1.Create a set of course codes.

2.Identify the discontinued course.

3.Remove it using discard() method.

4.Print the updated course codes.

DEFINATION OF COMMANDS USED

1.set(): Creates a new set.

2.frozenset(): Creates an immutable set.

3.add(): Adds an element to a set.

4.remove(): Removes a specified element from a set (raises error if not found).

5.discard(): Removes an element if present (no error if absent).

6.union() / |: Returns a set containing all elements from both sets.

7.intersection() / &: Returns common elements between sets.

8.difference() / -: Returns elements present in one set but not in another.

9.symmetric difference() / ^: Returns elements present in only one of the sets.

10.print(): Displays output on the screen.

CONCLUSION

In this experiment, we successfully studied the Set data type in Python and performed various operations on it. We observed that sets automatically remove duplicate values and do not support indexing. The experiment also demonstrated practical applications of sets such as finding unique values, common elements, and differences between groups. The use of frozenset showed how immutability can be enforced in Python. Thus, sets are highly useful for mathematical operations and data analysis tasks.
