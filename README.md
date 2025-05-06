# comp202-assignment-4-hashmap-implementation-solved
**TO GET THIS SOLUTION VISIT:** [COMP202 Assignment 4-Hashmap implementation Solved](https://www.ankitcodinghub.com/product/comp202-assignment-4-hashmap-implementation-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;96031&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;COMP202 Assignment 4-Hashmap implementation Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
Description

This assignment requires you to implement hashmaps with two different collision checking approaches, a hashmap based counter and a hashset. In addition, you are asked to solve an applied problem, calculating the co-occurence of words, using the data structures you have implemented.

The files you are given include comments to help you out. However, do not hesitate the contact us if anything is unclear.

Hashmaps

This assignment includes two hashmap versions with different collision handling approaches. One of them uses open addressing, specifically double hashing, and the other uses separate chaining, specifically linked-lists. Both of the approaches use multiply-add-divide (MAD) compression. These hashmaps implement the map interface and an abstract hashmap class. This abstract class has some common fields such as the parameters for the compression function and common methods. The design of these hashmaps rely on a hashentry class which represent the key-value pairs.

The files provided to you have comments that will help you with implementation. You can find the files related to hashmap part of the assignment below. Bold ones are the ones you need to modify and they are placed under the code folder, with the rest under given.

<ul>
<li>iMap.java: This file defines a simple map interface. Even though you do not need to modify this, make sure you read the comments in detail. It is pretty straight forward. This is same interface from the binary search tree assignment.</li>
<li>AbstractHashMap.java: This file includes common fields and methods for the hashmaps. The trivial methods are handled for you. The compression function parameters and the method that updates them based on the underlying array capacity are also given to you in this file. You might need to look at this class from time to time while implementing the hashmaps. Warning: Slighlty modified with the update.</li>
<li>HashEntry.java: This file includes the HashEntry class that describes a Key-Value pair for a hash- map. Certain useful methods are implemented for you. This is practically the same as the entry class we had from the binary search tree assignment. The skeleton of the hashmaps are designed such that the containers hold this type.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
• HashMapDH.java: This file has the base code for the hashmap that uses open addressing for col- lision handling with double hashing, namely the HashMapDH class. It extends the AbstractHashMap class and implements the iMap interface. Feel free to add more fields and methods. You are not allowed to use existing Java data structures apart from implementing the keySet method. The specific requirements are given as comments just before the class definition.

• HashMapSC.java: This file has the base code for the hashmap that uses separate chaining for collision handling with linked lists, namely the HashMapSC class. It extends the AbstractHashMap class and implements the iMap interface. Feel free to add more fields and methods. You are not allowed to use existing Java data structures apart from the secondary containers and implementing the keySet method. The specific requirements are given as comments just before the class defini- tion. Warning: Slighlty modified with the update.

Counter

A counter is an abstract data types that keeps track of how many times equivalent keys are added. It can be considered as a string-integer map with a couple of modifications. Its main operations are increment (put) and getCount (get). Some implementations allow for decrementing the count and/or removing the key altogether which we are not going to need.

In this part of the assignment, you are to implement a counter by wrapping around a hashmap. The counter will hold an internal hashmap (instead of extending it) which can be supplied from the outside. The class is setup such that you are only going to fill two methods, rest are handled for you. Make sure you understand the requirements of the increment and the getCount methods from the comments!

The only file that you need to work on for this part is the HashCounter.java file under the code folder.

Set

A set is an abstract data type that holds unique keys without any particular order. It can be considered as an implementation of the mathematical concept of a finite set. Its main operations are put, remove and contains which should be self-explanatory. Sets can be implemented by binary search trees or as hashsets and they do not involve key-value pairs, only keys. During the class, most of our examples for maps only had a key instead of a key-value pair so this part should not poe any difficulty.

In this part of the assignment, you are to implement such a set using hashing ideas. You can directly use one of your hashmap implementations and hide the value or you can implement a hashset from scratch. The former is easier, the latter will end up cleaner and faster. The files in this part of the assignment are below. Bold ones are the ones you need to modify and they are placed under the code folder, with the rest under given.

• iSet.java: This file defines a simple set interface. Even though you do not need to modify this, make sure you read the comments in detail. It has some differences with the map interface but is still pretty straight forward.

• HashSet.java: This file contains the farily empty definition the HashSet class with extends the set interface. You are free to design and implement it however you want. However, you are not allowed to use existing Java data structures apart from the secondary containers and implementing the keySet method.

Word Co-Occurrence

In fields related to computational linguistics, it is common to assume that semantically related terms appear occur together wihin a context. These terms are usually taken as words, which define the concept of word co-occurrence. The context can differ, from single sentences to entire documents.

This is the application part of the assignment. Given some text with multiple sentences, you are going to count the number of times two words appear together within a certain distance of each other in a single sentence. You are going to form a word co-occurrence matrix. This is a square matrix where row and column indices correspond to words and the specific entry in a given coordinate correspond to number of times that these two words occur together.

Suppose we are given the text “To be or not to be. That is the quetion.” and are asked to compute the co-occurence matrix. The context is given as 2 word neighbor distance in a sentence.

</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
The first step we are going to take is about finding the unique words (this does not need to be a separate step but helps the example). The set of unique words is {to,be,or,not,that,is,the,question}. It is common practice to convert to all lower case.

The second step is to separate the sentences which is trivial. The list of sentences is [to be or not to be, that is the question].

The third step is to iterate over these sentences. For each word, we find its neighbors within the given distance and jointly count them. For example:

<ul>
<li>For the first “to” in the first sentence, its neighbors are “be” and “or”. We set the entries that correspond to to-be and to-or to 1</li>
<li>For the first “be”, the neighbors are “to”, “or” and “not”. We set the entries that correspond to be-to, be-or and be-not to 1</li>
<li>For “or”, the neighbors are “to”, “be”, “not” and “be”. The entries should be set accordingly.</li>
<li>Skipping to the second “to”, the neighbors are “or”, “not” and “be”. We have seen to-be and to-or
before so we incement them to 2 and set to-not to 1.
</li>
</ul>
If we do it for all the words and sentences we get the following word co-occurence matrix:

to be or not that is the question to 0 2 2 1 0 0 0 0

be 2 0 1 2 0 0 0 0

or 2 1 0 1 0 0 0 0

not 1 2 1 0 0 0 0 0 that 0 0 0 0 0 1 1 0 is 0 0 0 0 1 0 1 1 the 0 0 0 0 1 1 0 1 question 0 0 0 0 0 1 1 0

Note that the matrix is symmetric. Co-occurrence matrices in general do not need to be symmetric but our definition of the context made it so.

For certain problems, it is desirable to ignore certain extremely common words such as the English articles “a”, “an”and “the”. Another, potentially harmful, appraoch is to ignore words that are shorther than two characters since they maybe one of the common words.

For other problems, there is only a set of keywords that we care about and want to calculate the co-occurence matrix just based on those, ignoring all the words.

The file HashBasedWordCo.java, has the skeleton of the code to implement this part. This class takes an entire text as a string and calculates the co-occurence matrix. The matrix is represented by a hashmap of string – hashcounter of string. A lot of support code such as loading files, pre-processing text and splitting the sentences are done for you. You should go over them. You need to complete two methods; (1) finding the unique words and (2) calculating the matrix. You may use anything you have implemented in this assignment but not allowed to use any other Java data structures apart from the given sentence lists. In fact, the class uses your implementation of hashmaps, hashcounters and hashsets. Warning: Slighlty modified with the update.

Testing

The Test.java has been updated and the file TestHashmap.java has been added to give your code a more thorough testing.

Warnings

All the methods that take a key as input should return null if the key is null. If the method return type is a primitive, it should return -1 if numeric and false if boolean. There are not any other options for this assignment.

Read all the comments, they are helpful. Let us know if they are confusing, contradictory or unclear.

The not implemented yet warnings are removed since it confused some of you. However, this means that it is up to you to make sure everything is implemented and not left empty!

</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
You are not allowed to use any default Java data structures other than to implement the keySet methods and for the secondary containers of the HashMapSC class. The HashBasedWordCO.java file has lists and arraylists for limited parts which you can use but do not add your own.

</div>
</div>
</div>
