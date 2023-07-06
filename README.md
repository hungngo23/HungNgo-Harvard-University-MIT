# HungNgo-Harvard-University-MIT

week 1:Lab 1: Population Growth
Determine how long it takes for a population to reach a particular size.

$ ./population
Start size: 100
End size: 200
Years: 9
Background
Say we have a population of n llamas. Each year, n / 3 new llamas are born, and n / 4 llamas pass away.

For example, if we were to start with n = 1200 llamas, then in the first year, 1200 / 3 = 400 new llamas would be born and 1200 / 4 = 300 llamas would pass away. At the end of that year, we would have 1200 + 400 - 300 = 1300 llamas.

To try another example, if we were to start with n = 1000 llamas, at the end of the year, we would have 1000 / 3 = 333.33 new llamas. We can’t have a decimal portion of a llama, though, so we’ll truncate the decimal to get 333 new llamas born. 1000 / 4 = 250 llamas will pass away, so we’ll end up with a total of 1000 + 333 - 250 = 1083 llamas at the end of the year.
----------------------------------
Week 2:Lab 2: Scrabble

Determine which of two Scrabble words is worth more.

$ ./scrabble
Player 1: COMPUTER
Player 2: science
Player 1 wins!
Implementation Details
Complete the implementation of scrabble.c, such that it determines the winner of a short scrabble-like game, where two players each enter their word, and the higher scoring player wins.
------------------------------------------------------------
Week 3: Algorithms
Lab 3: Sort:
Analyze three sorting programs to determine which algorithms they use.

Background
Recall from lecture that we saw a few algorithms for sorting a sequence of numbers: selection sort, bubble sort, and merge sort.

Selection sort iterates through the unsorted portions of a list, selecting the smallest element each time and moving it to its correct location.
Bubble sort compares pairs of adjacent values one at a time and swaps them if they are in the incorrect order. This continues until the list is sorted.
Merge sort recursively divides the list into two repeatedly and then merges the smaller lists back into a larger one in the correct order.
-----------------------------------------------------------
Week 4:Week 4 Memory
Pointers. Segmentation Faults. Dynamic Memory Allocation. Stack. Heap. Buffer Overflow. File I/O. Images.

Submit one of:
Smiley
Volume
-----------------------------------------------------------
Week 5:Week 5 Data Structures
Abstract Data Types. Queues, Stacks. Linked Lists. Trees, Binary Search Trees. Hash Tables. Tries.

Simulate the inheritance of blood types for each member of a family.

$ ./inheritance
Child (Generation 0): blood type OO
    Parent (Generation 1): blood type AO
        Grandparent (Generation 2): blood type OA
        Grandparent (Generation 2): blood type BO
    Parent (Generation 1): blood type OB
        Grandparent (Generation 2): blood type AO
        Grandparent (Generation 2): blood type BO
        Complete the implementation of inheritance.c, such that it creates a family of a specified generation size and assigns blood type alleles to each family member. The oldest generation will have alleles assigned randomly to them.

The create_family function takes an integer (generatio
-----------------------------------------------------------------
Week 6:Week 6 Python
Python: Functions, Arguments, Return Values; Variables; Boolean Expressions, Conditionals; Loops. Modules, Packages.
Write a program to run simulations of the FIFA World Cup.

$ python tournament.py 2018m.csv
Belgium: 20.9% chance of winning
Brazil: 20.3% chance of winning
Portugal: 14.5% chance of winning
Spain: 13.6% chance of winning
Switzerland: 10.5% chance of winning
Argentina: 6.5% chance of winning
England: 3.7% chance of winning
France: 3.3% chance of winning
Denmark: 2.2% chance of winning
Croatia: 2.0% chance of winning
Colombia: 1.8% chance of winning
Sweden: 0.5% chance of winning
Uruguay: 0.1% chance of winning
Mexico: 0.1% chance of winning
----------------------------------------------------------------------------
Week 7:Week 7 SQL
SQL: Tables; Types; Statements; Constraints; Indexes; Keywords, Functions; Transactions. Race Conditionals. SQL Injection Attacks.

Write SQL queries to answer questions about a database of songs.
Understanding
Provided to you is a file called songs.db, a SQLite database that stores data from Spotify about songs and their artists. This dataset contains the top 100 streamed songs on Spotify in 2018. In a terminal window, run sqlite3 songs.db so that you can begin executing queries on the database.

First, when sqlite3 prompts you to provide a query, type .schema and press enter. This will output the CREATE TABLE statements that were used to generate each of the tables in the database. By examining those statements, you can identify the columns present in each table.

Notice that every artist has an id and a name. Notice, too, that every song has a name, an artist_id (corresponding to the id of the artist of the song), as well as values for the danceability, energy, key, loudness, speechiness (presence of spoken words in a track), valence, tempo, and duration of the song (measured in milliseconds).

The challenge ahead of you is to write SQL queries to answer a variety of different questions by selecting data from one or more of these tables. After you do so, you’ll reflect on the ways Spotify might use this same data in their annual Spotify Wrapped campaign to characterize listeners’ habits.

Implementation Details
For each of the following problems, you should write a single SQL query that outputs the results specified by each problem. Your response must take the form of a single SQL query, though you may nest other queries inside of your query. You should not assume anything 

about the ids of any particular songs or artists: your queries should be accurate even if the id of any particular song or person were different. Finally, each query should return only the data necessary to answer the question: if the problem only asks you to output 
the names of songs, for example, then your query should not also output each song’s tempo.
------------------------------------------------------------
Week 8:HTML, CSS, JavaScript
Internet: Routers; TCP/IP; DNS. HTTP: URLs, GET, POST. HTML: Tags; Attributes. Servers. CSS: Properties; Selectors. Frameworks. JavaScript: Variables; Conditionals; Loops. Events.

Implementation Details
Design a webpage using HTML, CSS, and JavaScript to let users answer trivia questions.

In index.html, add beneath “Part 1” a multiple-choice trivia question of your choosing with HTML.
You should use an h3 heading for the text of your question.
You should have one button for each of the possible answer choices. There should be at least three answer choices, of which exactly one should be correct.
Using JavaScript, add logic so that the buttons change colors when a user clicks on them.
If a user clicks on a button with an incorrect answer, the button should turn red and text should appear beneath the question that says “Incorrect”.
If a user clicks on a button with the correct answer, the button should turn green and text should appear beneath the question that says “Correct!”.
In index.html, add beneath “Part 2” a text-based free response question of your choosing with HTML.
You should use an h3 heading for the text of your question.
You should use an input field to let the user type a response.
You should use a button to let the user confirm their answer.
Using JavaScript, add logic so that the text field changes color when a user confirms their answer.
If the user types an incorrect answer and presses the confirmation button, the text field should turn red and text should appear beneath the question that says “Incorrect”.
If the user types the correct answer and presses the confirmation button, the input field should turn green and text should appear beneath the question that says “Correct!”.
Optionally, you may also:

Edit styles.css to change the CSS of your webpage!
Add additional trivia questions to your trivia quiz if you would like!
______________-------------------------------------------------------------

Week 9:Week 9 Flask
Flask. Route. Decorators. Requests, Responses. Sessions. Cookies.
Create a web application to keep track of friends’ birthdays.
Complete the implementation of a web application to let users store and keep track of birthdays
------------------------------------------------------------------------------------
Week 10 :Week 10 Emoji
Precision. Unicode: Emoji, Code Points, ZWJ.
The climax of this course is its final project. The final project is your opportunity to take your newfound s
