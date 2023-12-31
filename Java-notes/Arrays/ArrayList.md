## what is ArrayList?
- An ArrayList is a resizable array, meaning its size can grow or shrink as needed.
- ArrayList can only store objects, not primitive data types like int, double, or char directly.
- To store primitives, you need to use their wrapper classes (e.g., Integer, Double, Character).
**Syntax:**

```java
ArrayList<dataType> arrayListName = new ArrayList<>();
```

### Operations in ArrayList

#### Adding Elements
- **append:** `add(element)` adds an element to the end of the ArrayList.

```java
ArrayList<String> cities = new ArrayList<>();
cities.add("New York");  // Append "New York"
cities.add("London");   // Append "London"
```

- **insert:** `add(index, element)` inserts an element at a specific index.

```java
cities.add(1, "Paris");  // Insert "Paris" at index 1
```
#### Retrieving Elements:

- `get(index)` returns the element at a specific index.

```java
String firstCity = cities.get(0);  // Get the first city ("New York")
```

#### Removing Elements:

- **by value:** `remove(element)` removes the first occurrence of a specific element.

```java
cities.remove("London");  // Remove "London"
```

- **by index:** `remove(index)` removes the element at a specific index.

```java
cities.remove(1);  // Remove the element at index 1 (now "Paris")
```

#### Checking Size:

- `size()` returns the number of elements in the ArrayList.

```java
int numCities = cities.size();  // Get the number of cities
```

### Difference between ArrayList and Array

| Feature | Array | ArrayList |
| ---- | ---- | ---- |
| Size | Fixed size, must be specified during declaration | Dynamic size, can grow or shrink as needed |
| Type of elements | Can store primitives (int, double, char, etc.) and objects | Can only store objects (primitives must be boxed in wrapper classes) |
| Performance | Generally faster for random access and basic operations | Slower for random access, but faster for insertion/removal at the end |
| Memory efficiency | More efficient for large, fixed collections | More efficient for small or frequently modified collections |
| Flexibility | less flexible because their size is fixed | more flexibility because they can grow or shrink dynamically |
| Declaration | `datatype[] arrayName = new datatype[size];` | `ArrayList<dataType> arrayListName = new ArrayList<>();` |
