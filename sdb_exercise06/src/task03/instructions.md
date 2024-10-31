# Task 6.3: SpellChecker

The following code uses a dictionary array of the most common 100 English words. We can use it as a spelling checker!

1. Define a `print()` method that takes a String array as an input parameter and prints out the first 10 
   words of 
   the 
   array. 

2. Write a `spellcheck()` method that takes a word and a String array as input parameters and returns true if the 
   word is in the
   array. It should return false if it is not found. Test your code by changing the word sent to the `spellcheck()`
   method in `main`. This algorithm is called a linear search where we step through the array one element at a time (here the dictionary one word at a time) looking for a certain element.

Add the requested methods into the given class:

```java
public class SpellChecker {

    /* 1. Write a print() method that takes an array as a parameter and prints out the first
     * 10 words of the array.
     */

    /* 2. Write a spellcheck() method that takes a word and an array as
     * parameters  and returns true if the word is in the array.
     * Return false if it is not found.
     */

    public static void main(String[] args) {
        String[] dictionary = {"the", "of", "and", "a", "to",
        "in", "is", "you", "that", "it", "he", "was", "for", "on",
        "are", "as", "with", "his", "they", "I", "at", "be",
        "this", "have", "from", "or", "one", "had", "by", "word",
        "but", "not", "what", "all", "were", "we", "when", "your",
        "can", "said", "there", "use", "an", "each", "which",
        "she", "do", "how", "their", "if", "will", "up", "other",
        "about", "out", "many", "then", "them", "these", "so",
        "some", "her", "would", "make", "like", "him", "into",
        "time", "has", "look", "two", "more", "write", "go",
        "see", "number", "no", "way", "could", "people", "my",
        "than", "first", "water", "been", "call", "who", "oil",
        "its", "now", "find", "long", "down", "day", "did", "get",
        "come", "made", "may", "cat", "dog", "cats", "dogs"};

     /* Uncomment to test Part 1
     print(dictionary);
     */

     /* Uncomment to test Part 2
     String word = "catz";
     if (spellcheck(word, dictionary) == true) {
         System.out.println(word + " is spelled correctly!");
     }
     else {
         System.out.println(word + " is misspelled!");
     }
     */
    }
}

```

3. Rewrite the `print()` and `spellcheck()` methods from the previous tasks to use an enhanced for-each loop instead of an indexed for-loop.

**Hints:** Strings cannot be compared with ==. This only compares the String references. Instead, the equals() method of the String class must be used, as it checks for content equality. Example:
```java
String s1 = "apple";
String s2 = "banana";
if (s1.equals(s2)) {
    System.out.println("Yes, they are equal!");
}

// Alternatively, you can also compare Strings and ignore upper and lower case:
s1.equalsIgnoreCase(s2);
```