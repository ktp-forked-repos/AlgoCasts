# AlgoCasts

本项目是 Udemy 上 Stephen Grider 老师，The Coding Interview Bootcamp: Algorithms + Data Structures 这个课程的仓库。

### 课程目录

- Get Started Here!
- A Touch of Setup
- [String Reversal](https://github.com/semlinker/AlgoCasts/blob/master/exercises/reversestring/index.js)
- [Palindromes](https://github.com/semlinker/AlgoCasts/blob/master/exercises/palindrome/index.js)
- [Integer Reversal](https://github.com/semlinker/AlgoCasts/blob/master/exercises/reverseint/index.js)
- [MaxChars](https://github.com/semlinker/AlgoCasts/blob/master/exercises/maxchar/index.js)
- [The Classic FizzBuzz!](https://github.com/semlinker/AlgoCasts/blob/master/exercises/fizzbuzz/index.js)
- [Array Chunking](https://github.com/semlinker/AlgoCasts/blob/master/exercises/chunk/index.js)
- [Anagrams](https://github.com/semlinker/AlgoCasts/blob/master/exercises/anagrams/index.js)
- [Sentence Capitalization](https://github.com/semlinker/AlgoCasts/blob/master/exercises/capitalize/index.js)
- [Printing Steps](https://github.com/semlinker/AlgoCasts/blob/master/exercises/steps/index.js)
- [Two Sided Steps - Pyramids](https://github.com/semlinker/AlgoCasts/blob/master/exercises/pyramid/index.js)
- [Find The Vowels](https://github.com/semlinker/AlgoCasts/blob/master/exercises/vowels/index.js)
- [Enter the Matrix Spiral](https://github.com/semlinker/AlgoCasts/blob/master/exercises/matrix/index.js)
- Runtime Complexity
- [Runtime Complexity in Practice - Fibonacci](https://github.com/semlinker/AlgoCasts/blob/master/exercises/fib/index.js)
- [The Queue](https://github.com/semlinker/AlgoCasts/blob/master/exercises/queue/index.js)
- [Underwater Queue Weaving](https://github.com/semlinker/AlgoCasts/blob/master/exercises/weave/index.js)
- [Stack 'Em Up With Stacks](https://github.com/semlinker/AlgoCasts/blob/master/exercises/stack/index.js)
- [Two Become One](https://github.com/semlinker/AlgoCasts/blob/master/exercises/qfroms/index.js)
- [Linked Lists](https://github.com/semlinker/AlgoCasts/blob/master/exercises/linkedlist/index.js)
- [Find the Midpoint](https://github.com/semlinker/AlgoCasts/blob/master/exercises/midpoint/index.js)
- [Circular Lists?](https://github.com/semlinker/AlgoCasts/blob/master/exercises/circular/index.js)
- [Step Back From the Tail](https://github.com/semlinker/AlgoCasts/blob/master/exercises/fromlast/index.js)
- [Building a Tree](https://github.com/semlinker/AlgoCasts/blob/master/exercises/tree/index.js)
- [Tree Width with Level Width](https://github.com/semlinker/AlgoCasts/blob/master/exercises/levelwidth/index.js)
- [My Best Friend, Binary Search Trees](https://github.com/semlinker/AlgoCasts/blob/master/exercises/bst/index.js)
- [Validating a Binary Search Tree](https://github.com/semlinker/AlgoCasts/blob/master/exercises/validate/index.js)
- [Back to Javascript - Events](https://github.com/semlinker/AlgoCasts/blob/master/exercises/events/index.js)
- Building Twitter - A Design Question
- [Sorting With BubbleSort](https://github.com/semlinker/AlgoCasts/blob/master/exercises/sorting/index.js)
- [Sort By Selection](https://github.com/semlinker/AlgoCasts/blob/master/exercises/sorting/index.js)
- [Ack, MergeSort!](https://github.com/semlinker/AlgoCasts/blob/master/exercises/sorting/index.js)

### 项目简介

#### 目录结构

```
├── LICENSE
├── README.md   # 项目简介
├── completed_exercises # 习题答案
├── diagrams # 答题解析所用图例
└── exercises # 习题目录
```

#### 项目启动

1、全局安装 [jest](https://github.com/facebook/jest)：

```shell
$ npm i -g jest
```

> 本课程会大量使用 ES2015+ 的新特性，为了避免出现任何可能的错误，请保证你本地安装的 Node.js 版本为 8.0 以上的版本。

2、运行测试用例：

```shell
$ cd exercises
$ jest reversestring/test.js
```

运行结果示例：

```
 PASS  reversestring/test.js
  ✓ Reverse function exists (3ms)
  ✓ Reverse reverses a string (2ms)
  ✓ Reverse reverses a string

Test Suites: 1 passed, 1 total
Tests:       3 passed, 3 total
Snapshots:   0 total
Time:        0.757s
```

### 习题题干

#### String Reversal

```javascript
// --- Directions
// Given a string, return a new string with the reversed
// order of characters
// --- Examples
//   reverse('apple') === 'leppa'
//   reverse('hello') === 'olleh'
//   reverse('Greetings!') === '!sgniteerG'

function reverse(str) {}
```

#### Palindromes

```javascript
// --- Directions
// Given a string, return true if the string is a palindrome
// or false if it is not.  Palindromes are strings that
// form the same word if it is reversed. *Do* include spaces
// and punctuation in determining if the string is a palindrome.
// --- Examples:
//   palindrome("abba") === true
//   palindrome("abcdefg") === false

function palindrome(str) {}
```

#### Integer Reversal

```javascript
// --- Directions
// Given an integer, return an integer that is the reverse
// ordering of numbers.
// --- Examples
//   reverseInt(15) === 51
//   reverseInt(981) === 189
//   reverseInt(500) === 5
//   reverseInt(-15) === -51
//   reverseInt(-90) === -9

function reverseInt(n) {}
```

#### MaxChars

```javascript
// --- Directions
// Given a string, return the character that is most
// commonly used in the string.
// --- Examples
// maxChar("abcccccccd") === "c"
// maxChar("apple 1231111") === "1"

function maxChar(str) {}
```

#### The Classic FizzBuzz!

```javascript
// --- Directions
// Write a program that console logs the numbers
// from 1 to n. But for multiples of three print
// “fizz” instead of the number and for the multiples
// of five print “buzz”. For numbers which are multiples
// of both three and five print “fizzbuzz”.
// --- Example
//   fizzBuzz(5);
//   1
//   2
//   fizz
//   4
//   buzz

function fizzBuzz(n) {}
```

#### Array Chunking

```javascript
// --- Directions
// Given an array and chunk size, divide the array into many subarrays
// where each subarray is of length size
// --- Examples
// chunk([1, 2, 3, 4], 2) --> [[ 1, 2], [3, 4]]
// chunk([1, 2, 3, 4, 5], 2) --> [[ 1, 2], [3, 4], [5]]
// chunk([1, 2, 3, 4, 5, 6, 7, 8], 3) --> [[ 1, 2, 3], [4, 5, 6], [7, 8]]
// chunk([1, 2, 3, 4, 5], 4) --> [[ 1, 2, 3, 4], [5]]
// chunk([1, 2, 3, 4, 5], 10) --> [[ 1, 2, 3, 4, 5]]

function chunk(array, size) {}
```

#### Anagrams

```javascript
// --- Directions
// Check to see if two provided strings are anagrams of eachother.
// One string is an anagram of another if it uses the same characters
// in the same quantity. Only consider characters, not spaces
// or punctuation.  Consider capital letters to be the same as lower case
// --- Examples
//   anagrams('rail safety', 'fairy tales') --> True
//   anagrams('RAIL! SAFETY!', 'fairy tales') --> True
//   anagrams('Hi there', 'Bye there') --> False

function anagrams(stringA, stringB) {}
```

#### Sentence Capitalization

```javascript
// --- Directions
// Write a function that accepts a string.  The function should
// capitalize the first letter of each word in the string then
// return the capitalized string.
// --- Examples
//   capitalize('a short sentence') --> 'A Short Sentence'
//   capitalize('a lazy fox') --> 'A Lazy Fox'
//   capitalize('look, it is working!') --> 'Look, It Is Working!'

function capitalize(str) {}
```

#### Printing Steps

```javascript
// --- Directions
// Write a function that accepts a positive number N.
// The function should console log a step shape
// with N levels using the # character.  Make sure the
// step has spaces on the right hand side!
// --- Examples
//   steps(2)
//       '# '
//       '##'
//   steps(3)
//       '#  '
//       '## '
//       '###'
//   steps(4)
//       '#   '
//       '##  '
//       '### '
//       '####'

function steps(n) {}
```

#### Two Sided Steps - Pyramids

```javascript
// --- Directions
// Write a function that accepts a positive number N.
// The function should console log a pyramid shape
// with N levels using the # character.  Make sure the
// pyramid has spaces on both the left *and* right hand sides
// --- Examples
//   pyramid(1)
//       '#'
//   pyramid(2)
//       ' # '
//       '###'
//   pyramid(3)
//       '  #  '
//       ' ### '
//       '#####'

function pyramid(n) {}
```

#### Enter the Matrix Spiral

```javascript
// --- Directions
// Write a function that returns the number of vowels
// used in a string.  Vowels are the characters 'a', 'e'
// 'i', 'o', and 'u'.
// --- Examples
//   vowels('Hi There!') --> 3
//   vowels('Why do you ask?') --> 4
//   vowels('Why?') --> 0

function vowels(str) {}
```

#### Runtime Complexity in Practice - Fibonacci

```javascript
// --- Directions
// Print out the n-th entry in the fibonacci series.
// The fibonacci series is an ordering of numbers where
// each number is the sum of the preceeding two.
// For example, the sequence
//  [0, 1, 1, 2, 3, 5, 8, 13, 21, 34]
// forms the first ten entries of the fibonacci series.
// Example:
//   fib(4) === 3

function fib(n) {}
```

#### The Queue

```javascript
// --- Description
// Create a queue data structure.  The queue
// should be a class with methods 'add' and 'remove'.
// Adding to the queue should store an element until
// it is removed
// --- Examples
//     const q = new Queue();
//     q.add(1);
//     q.remove(); // returns 1;

class Queue {}
```

#### Underwater Queue Weaving

```javascript
// --- Directions
// 1) Complete the task in weave/queue.js
// 2) Implement the 'weave' function.  Weave
// receives two queues as arguments and combines the
// contents of each into a new, third queue.
// The third queue should contain the *alterating* content
// of the two queues.  The function should handle
// queues of different lengths without inserting
// 'undefined' into the new one.
// *Do not* access the array inside of any queue, only
// use the 'add', 'remove', and 'peek' functions.
// --- Example
//    const queueOne = new Queue();
//    queueOne.add(1);
//    queueOne.add(2);
//    const queueTwo = new Queue();
//    queueTwo.add('Hi');
//    queueTwo.add('There');
//    const q = weave(queueOne, queueTwo);
//    q.remove() // 1
//    q.remove() // 'Hi'
//    q.remove() // 2
//    q.remove() // 'There'

const Queue = require('./queue');

function weave(sourceOne, sourceTwo) {}
```

#### Stack 'Em Up With Stacks

```javascript
// --- Directions
// Create a stack data structure.  The stack
// should be a class with methods 'push', 'pop', and
// 'peek'.  Adding an element to the stack should
// store it until it is removed.
// --- Examples
//   const s = new Stack();
//   s.push(1);
//   s.push(2);
//   s.pop(); // returns 2
//   s.pop(); // returns 1

class Stack {}
```

#### Two Become One

```javascript
// --- Directions
// Implement a Queue datastructure using two stacks.
// *Do not* create an array inside of the 'Queue' class.
// Queue should implement the methods 'add', 'remove', and 'peek'.
// For a reminder on what each method does, look back
// at the Queue exercise.
// --- Examples
//     const q = new Queue();
//     q.add(1);
//     q.add(2);
//     q.peek();  // returns 1
//     q.remove(); // returns 1
//     q.remove(); // returns 2

const Stack = require('./stack');

class Queue {}
```

#### Linked Lists

```javascript
// --- Directions
// Implement classes Node and Linked Lists
// See 'directions' document

class Node {}

class LinkedList {}
```

#### Find the Midpoint

```javascript
// --- Directions
// Return the 'middle' node of a linked list.
// If the list has an even number of elements, return
// the node at the end of the first half of the list.
// *Do not* use a counter variable, *do not* retrieve
// the size of the list, and only iterate
// through the list one time.
// --- Example
//   const l = new LinkedList();
//   l.insertLast('a')
//   l.insertLast('b')
//   l.insertLast('c')
//   midpoint(l); // returns { data: 'b' }

function midpoint(list) {}
```

#### Circular Lists?

```javascript
// --- Directions
// Given a linked list, return true if the list
// is circular, false if it is not.
// --- Examples
//   const l = new List();
//   const a = new Node('a');
//   const b = new Node('b');
//   const c = new Node('c');
//   l.head = a;
//   a.next = b;
//   b.next = c;
//   c.next = b;
//   circular(l) // true

function circular(list) {}
```

#### Step Back From the Tail

```javascript
// --- Directions
// Given a linked list, return the element n spaces
// from the last node in the list.  Do not call the 'size'
// method of the linked list.  Assume that n will always
// be less than the length of the list.
// --- Examples
//    const list = new List();
//    list.insertLast('a');
//    list.insertLast('b');
//    list.insertLast('c');
//    list.insertLast('d');
//    fromLast(list, 2).data // 'b'

function fromLast(list, n) {}
```

#### Building a Tree

```javascript
// --- Directions
// 1) Create a node class.  The constructor
// should accept an argument that gets assigned
// to the data property and initialize an
// empty array for storing children. The node
// class should have methods 'add' and 'remove'.
// 2) Create a tree class. The tree constructor
// should initialize a 'root' property to null.
// 3) Implement 'traverseBF' and 'traverseDF'
// on the tree class.  Each method should accept a
// function that gets called with each element in the tree

class Node {}

class Tree {}
```

#### Tree Width with Level Width

```javascript
// --- Directions
// Given the root node of a tree, return
// an array where each element is the width
// of the tree at each level.
// --- Example
// Given:
//     0
//   / |  \
// 1   2   3
// |       |
// 4       5
// Answer: [1, 3, 2]

function levelWidth(root) {}
```

#### My Best Friend, Binary Search Trees

```javascript
// --- Directions
// 1) Implement the Node class to create
// a binary search tree.  The constructor
// should initialize values 'data', 'left',
// and 'right'.
// 2) Implement the 'insert' method for the
// Node class.  Insert should accept an argument
// 'data', then create an insert a new node
// at the appropriate location in the tree.
// 3) Implement the 'contains' method for the Node
// class.  Contains should accept a 'data' argument
// and return the Node in the tree with the same value.

class Node {}
```

#### Validating a Binary Search Tree

```javascript
// --- Directions
// Given a node, validate the binary search tree,
// ensuring that every node's left hand child is
// less than the parent node's value, and that
// every node's right hand child is greater than
// the parent

function validate(node, min = null, max = null) {}
```

#### Back to Javascript - Events

```javascript
// --- Directions
// Create an 'eventing' library out of the
// Events class.  The Events class should
// have methods 'on', 'trigger', and 'off'.

class Events {
  // Register an event handler
  on(eventName, callback) {}

  // Trigger all callbacks associated
  // with a given eventName
  trigger(eventName) {}

  // Remove all event handlers associated
  // with the given eventName
  off(eventName) {}
}
```

#### Sorting With BubbleSort

```javascript
// --- Directions
// Implement bubbleSort, selectionSort, and mergeSort

function bubbleSort(arr) {}

function selectionSort(arr) {}

function mergeSort(arr) {}

function merge(left, right) {}
```

### FAQ

#### 如何查看 diagrams 目录下的文件

该项目中的所使用的图例是通过 [draw.io](https://www.draw.io/) 在线绘图工具生成，因此我们可以使用它提供的预览功能实现文件预览：

1、打开 [Online Diagram Viewer](https://jgraph.github.io/drawio-tools/tools/viewer.html) 页面；

2、获取预览文件的完整地址，比如：

```xml
https://raw.githubusercontent.com/semlinker/AlgoCasts/master/diagrams/01/diagrams.xml
```

3、在 [Online Diagram Viewer](https://jgraph.github.io/drawio-tools/tools/viewer.html) 页面页面中，**Link to Diagram** 输入框内输入以上地址，输入完成后点击 **Click Here!** 按钮。

除了预览功能之外，[drawio-tools](https://jgraph.github.io/drawio-tools/) 还提供了其他工具，有兴趣的小伙伴可以了解一下。