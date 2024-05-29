# LeetCode

Solutions for LeetCode in <s>***C++***</s>\*, ***Python***, ***Rust***\*\*, and ***SQL***.

\* Discontinued. Existing C++ solutions are kept for reference.\
\*\* Currently learning Rust with the problems provided.

![Leetcode Stats](https://leetcard.jacoblin.cool/kizzandev?hide=ranking,easy-solved-count,medium-solved-count,hard-solved-count&font=Edu+TAS+Beginner)

<!-- -->

## Project structure

<details>
<summary>
Click to expand!
</summary>

```mermaid
%%{init: {'flowchart' : {'curve' : 'linear'}}}%%
graph LR;
    ROOT((ROOT))
    ROOT-->C++
    ROOT-->Python
    ROOT-->Rust
    ROOT-->SQL[("&nbsp;&nbsp;SQL&nbsp;&nbsp;")]
    C++-->Problem_x
    Python-->Problem_x
    Rust-->Problem_folder
    Problem_folder-->src
    src-->Problem_x
    SQL-->Problem_x
```
</details>

## Custom map

<!--<details>
<summary>
Click to expand!
</summary>-->

<!-- type: HIGHLIGHT -->

```mermaid
%%{init: { 'logLevel': 'debug', 'theme': 'dark', 'gitGraph': {'showBranches': true, 'parallelCommits':true}, 'themeVariables': {
              'commitLabelBackground': '#00000000',
              'commitLabelColor': '#ffffff',
              'commitLabelFontSize': '16px',
              'gitInv0': '#00ff00'
       } } }%%
gitGraph
    branch arrHash
    checkout arrHash
    commit id: "242. Valid Anagram" tag:"🟢"
    commit id: "49. Group Anagrams" tag:"🟡"
    commit id: "238. Product of Array Except Self" tag:"🟡"
    commit id: "36. Valid Sudoku" tag:"🟡"
    commit id: "347. Top K Frequent Elements" tag:"🟡"
    commit id: "128. Longest Consecutive Sequence" tag:"🟡"
    commit id: "121. Best Time to Buy and Sell Stock" tag:"🟢"
    commit id: "65. Valid Number" tag:"🔴"
    branch stack
    checkout stack
    commit id: "155. Min Stack" tag:"🟡"
    commit id: "150. Evaluate Reverse Polish Notation" tag:"🟡"
    commit id: "739. Daily Temperatures" tag:"🟡"
    commit id: "84. Largest Rectangle in Histogram" tag:"🔴"
    branch twoPointers
    checkout twoPointers
    commit id: "125. Valid Palindrome" tag:"🟢"
    commit id: "167. Two Sum II - Input Array is Sorted" tag:"🟡"
    commit id: "42. Trapping Rain Water" tag:"🔴"
    branch slidingWindow
    checkout slidingWindow
    commit id: "3. Longest Substring Without Repeating Characters" tag:"🟡"
    commit id: "76. Minimum Window Substring" tag:"🔴"
    commit id: "239. Sliding Window Maximum" tag:"🔴"
    branch linkedList
    checkout linkedList
    commit id: "206. Reverse Linked List" tag:"🟢"
    commit id: "21. Merge Two Sorted Lists" tag:"🟢"
    # branch binarySearch
    # checkout binarySearch
    # branch trees
    # checkout trees
    # branch heap
    # checkout heap
    # branch backtracking
    # checkout backtracking
    # branch graphs
    # checkout graphs
    # branch moreGraphs
    # checkout moreGraphs
    # branch dynProgramming
    # checkout dynProgramming
```
<!--</details>-->

## Gantt Chart

### LeetCode 75

<details>
<summary>
Click to expand!
</summary>

<!-- title : (empty|active|done) , name , after name , 1d -->
```mermaid
gantt
    section Array/Str
    Merge Strings Alternately               : done,   a0, 2000-01-01, 1d
    Greatest Common Divisor of Strings      : done,   a,  2000-01-01, 1d
    Kids With the Greatest Number of Candies: done,   a,  2000-01-01, 1d
    Can Place Flowers                       : done,   a,  2000-01-01, 1d
    Reverse Vowels of a String              : done,   a,  2000-01-01, 1d
    Reverse Words in a String               : active  a,  2000-01-01, 1d
    Product of Array Except Self            :         a,  2000-01-01, 1d
    Increasing Triplet Subsequence          :         a,  2000-01-01, 1d
    String Compression                      :         a,  2000-01-01, 1d

    section Two Pointers
    Move Zeroes              :         a1, after a0, 1d
    Is Subsequence           :         a , after a0, 1d
    Container With Most Water:         a , after a0, 1d
    Max Number of K-Sum Pairs:         a , after a0, 1d

    section Sliding Window
    Maximum Average Subarray I                             :         a2, after a1, 1d
    Maximum Number of Vowels in a Substring of Given Length:         a , after a1, 1d
    Max Consecutive Ones III                               :         a , after a1, 1d
    Longest Subarray of 1's After Deleting One Element     :         a , after a1, 1d

    section Prefix Sum
    Find the Highest Altitude:         a3, after a2, 1d
    Find Pivot Index         :         a , after a2, 1d
```
</details>

### SQL 50

<details>
<summary>
Click to expand!
</summary>

```mermaid
gantt
    section Select
    Recyclable and Low Fat Products: done,   a0, 2000-01-01, 1d
    Find Customer Referee          : done,   a , 2000-01-01, 1d
    Big Countries                  : done,   a , 2000-01-01, 1d
    Article Views I                : done,   a , 2000-01-01, 1d
    Invalid Tweets                 : done,   a , 2000-01-01, 1d

    section Basic Joins
    Replace Employee ID With The Unique Identifier        : done,   a1, after a0, 1d
    Product Sales Analysis I                              : done,   a , after a0, 1d
    Customer Who Visited but Did Not Make Any Transactions: done,   a , after a0, 1d
    Rising Temperature                                    : active, a , after a0, 1d
    Average Time of Process per Machine                   :         a , after a0, 1d
    Employee Bonus                                        :         a , after a0, 1d
    Students and Examinations                             :         a , after a0, 1d
    Managers with at Least 5 Direct Reports               :         a , after a0, 1d
    Confirmation Rate                                     :         a , after a0, 1d
```
</details>
