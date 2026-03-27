# ☕ Java DSA Cheatsheet

> Quick reference for commonly used Java constructs, data structures, and utilities in competitive programming and DSA problem solving.

---

## 📌 Constants & Utilities

```java
int max = Integer.MIN_VALUE;  // Use when tracking maximum (start from lowest)
int min = Integer.MAX_VALUE;  // Use when tracking minimum (start from highest)
int mod = 1000000007;         // Standard modulo for large number problems
```

---

## 🔁 Swap

```java
int temp = a;
a = b;
b = temp;
```

---

## 🧵 StringBuilder

```java
StringBuilder sb = new StringBuilder();       // Empty StringBuilder
StringBuilder sb = new StringBuilder(s);      // From existing String
```

| Method | Description |
|--------|-------------|
| `sb.append("hello")` | Appends `"hello"` to the end |
| `sb.insert(5, "hello")` | Inserts `"hello"` at index `5` |
| `sb.delete(5, 10)` | Deletes characters from index `5` to `9` (exclusive of 10) |
| `sb.deleteCharAt(index)` | Deletes character at `index` |
| `sb.replace(5, 10, "world")` | Replaces characters from index `5` to `9` with `"world"` |
| `sb.reverse()` | Reverses the StringBuilder |
| `sb.length()` | Returns length |
| `sb.charAt(index)` | Returns character at `index` |
| `sb.setCharAt(index, 'y')` | Sets character at `index` to `'y'` |
| `sb.substring(5, 10)` | Returns substring from index `5` to `9` |
| `sb.substring(5)` | Returns substring from index `5` to end |
| `sb.toString()` | Converts to `String` |
| `sb.indexOf("world")` | Index of first occurrence of `"world"` |
| `sb.lastIndexOf("world")` | Index of last occurrence of `"world"` |

---

## 🔤 Character Utilities

```java
Character.isDigit(c)       // true if c is a digit
Character.isLetter(c)      // true if c is a letter
Character.isUpperCase(c)   // true if c is uppercase
Character.isLowerCase(c)   // true if c is lowercase
Character.toLowerCase(c)   // converts c to lowercase
Character.toUpperCase(c)   // converts c to uppercase
```

---

## 🔢 Math Utilities

```java
Math.max(a, b)   // returns maximum of a, b
Math.min(a, b)   // returns minimum of a, b
```

---

## 📋 ArrayList

```java
ArrayList<Integer> list = new ArrayList<>();
```

| Method | Description |
|--------|-------------|
| `list.add(x)` | Adds element `x` |
| `list.get(i)` | Gets element at index `i` |
| `list.set(i, val)` | Sets element at index `i` to `val` |
| `list.remove(i)` | Removes element at index `i` |
| `list.size()` | Returns size of list |

### Sorting & Reversing

```java
Arrays.sort(arr);              // Sort primitive array
Collections.sort(list);        // Sort ArrayList
Collections.reverse(list);     // Reverse ArrayList
```

---

## 📚 Stack

```java
Stack<Integer> st = new Stack<>();
```

| Method | Description |
|--------|-------------|
| `st.push(x)` | Pushes `x` onto stack |
| `st.pop()` | Removes and returns top element |
| `st.peek()` | Returns top element without removing |
| `st.isEmpty()` | Returns `true` if stack is empty |

---

## 🚶 Queue

```java
Queue<Integer> q = new LinkedList<>();
```

| Method | Description |
|--------|-------------|
| `q.offer(x)` | Adds `x` to the queue |
| `q.poll()` | Removes and returns front element |
| `q.peek()` | Returns front element without removing |

---

## ↔️ Deque (Double-Ended Queue)

```java
Deque<Integer> dq = new ArrayDeque<>();
```

| Method | Description |
|--------|-------------|
| `dq.addFirst(x)` | Adds `x` to the front |
| `dq.addLast(x)` | Adds `x` to the back |
| `dq.removeFirst()` | Removes and returns front element |
| `dq.removeLast()` | Removes and returns back element |

---

## 🗺️ HashMap

```java
HashMap<Integer, Integer> map = new HashMap<>();
```

| Method | Description |
|--------|-------------|
| `map.put(key, value)` | Inserts/updates key-value pair |
| `map.get(key)` | Returns value for `key` |
| `map.getOrDefault(key, 0)` | Returns value or `0` if key absent |
| `map.containsKey(key)` | Returns `true` if key exists |
| `map.remove(key)` | Removes the key-value pair |

---

## 🗂️ HashSet

```java
HashSet<Integer> set = new HashSet<>();
```

| Method | Description |
|--------|-------------|
| `set.add(x)` | Adds element `x` |
| `set.contains(x)` | Returns `true` if `x` is present |
| `set.remove(x)` | Removes element `x` |

---

## ⛰️ Priority Queue (Min-Heap)

```java
PriorityQueue<Integer> pq = new PriorityQueue<>();  // Min-Heap by default
```

> For **Max-Heap**: `PriorityQueue<Integer> pq = new PriorityQueue<>(Collections.reverseOrder());`

| Method | Description |
|--------|-------------|
| `pq.add(x)` | Adds element `x` |
| `pq.poll()` | Removes and returns the smallest element |
| `pq.peek()` | Returns smallest element without removing |

---

*Happy Coding! 🚀*
