say-16

Today started nice and easy. I started with learning some dart programming fundamentals.

The first topic was about Lists, A very commonly used collection in programming is an array. Dart represents arrays in the form of List objects. A List is simply an ordered group of objects. Index of the element represents the position of the specific data and when the list item of that index is called the element is displayed. Generally, the list item is called from its index.Types of List – 

There are broadly two types of list on the basis of its length: 

Fixed Length List

Growable List

 

Fixed Length List

Here, the size of the list is declared initially and can’t be changed during runtime.

Growthable List

This type of list is declared without declaring size of the list. Its length can be changed during runtime.

Then coming to Sets, Sets in Dart is a special case in List where all the inputs are unique i.e it doesn’t contain any repeated input. It can also be interpreted as an unordered array with unique inputs. The set comes into play when we want to store unique values in a single variable without considering the order of the inputs. The sets are declared by the use of a set keyword. 

Furthermore, I learned about maps. Maps are dictionary-like data types that exist in key-value form (known as lock-key). There is no restriction on the type of data that goes in a map data type. Maps are very flexible and can mutate their size based on the requirements. However, it is important to note that all locks (keys) need to be unique inside a map data type.

I also learned about null safety, Null Safety in simple words means a variable cannot contain a ‘null’ value unless you initialized null to that variable. With null safety, all the runtime null-dereference errors will now be shown in compile time.

When we use null safety, all the types are non-nullable by default. For example, when we declare a variable of type int, the variable will contain some integer value.  

Non-nullable variables must always be initialized with non-null values.


Nullable Types

To specify if the variable can be null, then you can use the nullable type ?        operator, for Eg:

String? carName;  // initialized to null by default

int? marks = 36;  // initialized to non-null

marks = null; // can be re-assigned to null

Note: You don’t need to initialize a nullable variable before using it. It is initialized to null by default.

The Assertion Operator (!)

Use the null assertion operator ( ! ) to make Dart treat a nullable expression as non-nullable if you’re certain it isn’t null.

?? operator can be used to cherry pick non null values, for eg:

Void test() {

const String? firstName=null;

const String? midName=’bla’;

const String? lastName=’blazz’;

To see the first non null value

We can type

const firstNonNullValue = firstName??midName??lastName;


Next came the null aware assignment operator( ??=)

This can be used like:

name??= lastName; → if name is null assign lastName to it and check whether lastName is null;

The other operands were, the conditional invocation operator or ?. 

?. is used to invoke a method or property. For eg:

Void test(List<String>?names)

final length = names?. Length?? 0;  → if names’ value is not null then grab length or take the value of 0 and assign it to length. 


Then there was a session by  Mr Askin about Arrays. An array is a special variable, which can hold more than one value. 

An array can carry anything from primitive data types to functions, objects and even another array itself. The syntax of an array looks like this:

const array_name = [item1, item2, ...]; 

Then he asked us to check the documentation about arrays in the mdn website to learn about different array properties like;

Array.prototype.fill()

Fills all the elements of an array from a start index to an end index with a static value.

Array.prototype.filter()

Returns a new array containing all elements of the calling array for which the provided filtering function returns true.

Array.prototype.find()

Returns the found element in the calling array, if some element in the array satisfies the testing function, or undefined if not found.

Array.prototype.findIndex()

Returns the found index in the calling array, if an element in the array satisfies the testing function, or -1 if not found.

Array.prototype.map()

Returns a new array containing the results of invoking a function on every element in the calling array.

 push() method to append a new string to the array

pop() method to remove the last item from the array.

splice() method to remove the last 3 items from the array.

shift() method to remove the first item from the array


