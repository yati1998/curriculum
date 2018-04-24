# Searching Algorithms

### Projected Time
- Video: 30 min
- Exercises: 2-3 hours

### Prerequisites
- Arrays

### Motivation
Searching for an item in an array is a common need. Software developers should know the possible algorithms for searching and which is best for different use cases.

### Objectives
**Apprentices will be able to**:
- Understand what algorithms are
- Understand how linear and binary search work
- Understand the runtime of linear and binary search
- Know when to use linear and binary search

### Materials

- [Linear search video](https://www.youtube.com/watch?v=vZWfKBdSgXI)
- [Binary search video](https://www.youtube.com/watch?v=5xlIPT1FRcA)

Additional resources:
- [Linear and binary search](https://medium.com/@connorleech/implement-linear-and-binary-search-algorithms-with-javascript-2149997588f0)
- [In-depth articles about binary search](https://www.khanacademy.org/computing/computer-science/algorithms/binary-search/a/binary-search)
- [More about log(n)](https://hackernoon.com/what-does-the-time-complexity-o-log-n-actually-mean-45f94bb5bfbf)
- [Linear + binary search video](https://www.youtube.com/watch?v=wNVCJj642n4)
- [Binary search + code implementation video](https://www.youtube.com/watch?v=P3YID7liBug)


### Mini Lesson

What is an algorithm? Think about how you make a sandwich. Does the order you put the ingredients matter? (You may think no, but can the outermost ingredient be anything?) Sometimes the steps of algorithms are really important (like bread has to come first, and usually it's eaiser to put sauce on the bread) and sometimes it doesn't matter (turkey, cheese, lettuce, tomato, or other additives can usually go in any order).

Sometimes people come up with new and creative ways to do algorithms that can be more efficient (save time, memory, or hard drive space). You can make a peanut butter and jelly sandwich by putting peanut butter on one slice of bread, jelly on another, then putting them together. It works, but it can be quite messy. If you take the peanut butter side and make an extra thicker ring around it, the jelly can go inside of that instead. Now the jelly is enclosed and doesn't make a mess as you eat it.

Think about a shuffled deck of cards. Let's say you're looking for the 6 of hearts. How do you find it? You could just start grabbing random cards until you find it. If you grab a card and say "this isn't it" and put it back, you really could be looking for a long time. Starting at the top of the deck and looking at each card one by one, you're guaranteed to find it. This is the basis of a linear search.

If you have a phone book, and you're looking for Jessica Smith, do you start on page 1 and read every name until you find her? Probably not. By starting in the middle, flipping larger chunks of pages until you get to the Ss, then eventually finding Smith, then finding Jessica eliminates a TON of time. This is the idea behind a binary search.

All of these algorithms are pretty common, and have standard implementations in most programming languages. But understanding how they work and when to use one over another will help you write better software.

Watch the video to learn more details about linear and binary search algorithms!

Slides: https://docs.google.com/presentation/d/1x8xO_URwZVoB4JxTNN90z0sHSxoYEq0INOH_IIi8SLE/edit#slide=id.p

Video: https://drive.google.com/open?id=1iHgUlPK2G9Gk3mbdOSObUKOFld_mALrs

### Common Mistakes / Misconceptions
- Binary search can only be used on sorted arrays
- Binary search is not always faster than linear search -- for small arrays, linear search can be faster

### Independent Practice

- Write a linear search to find a given item in an array. The function should take in an array of strings and a string to search for, and return whether that string is in the array

- Write a linear search to find the largest item in an array. The function should take in an array of integers and return the largest integer.

- Say you have an array and want to find the number closest to a given number n. Write a linear search to find the closest number.
E.g. if the array is [4, 1, 6, 8] and n=3, your function should return 4.

- How long does linear search take for large arrays vs binary search? Draw a graph with values 1 to 100 on the x-axis. Graph a linear function (y=x) and a log function (y=log<sub>2</sub>(n))

### Challenge

- Write binary search to find a given item in an array. You can write it yourself, or use this tutorial for some guidance: https://www.khanacademy.org/computing/computer-science/algorithms/binary-search/p/challenge-binary-search


### Check for Understanding

Make a cheat sheet answering the following questions for linear search and binary search:
- What is it?
- What types of arrays can you use it on?
- What is the runtime?