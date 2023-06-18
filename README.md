## **How to setup**

1. Clone the repo
2. Place your BinomialHeap.java file inside the src folder
3. Open the project in your favorite IDE (Eclipse, VScode, Intellij ...)
4. Run MainTester.java as a JUnit Test



## **Running java files as a Unit Test:**

### **1)** In **Intellij**, simply right click the file `"MainTester.java"` and click on: `'run MainTester'`.

![Screenshot showing how to run junit test in intellij](https://i.imgur.com/FRHMGKP.jpg)

### **2)** In **Vscode**, Once you open the folder, Youll have a lab flask icon on the left, click on it and youll be greeeted with a window to run your tests. Hover over MainTester and click on the play button next to it on the far right.

![Screenshot showing how to run junit test in intellij](https://i.imgur.com/YPD13MO.jpg)

### **3)** (Least recommended) In **Eclipse** right click `MainTester.java` and choose `Run as` > `Junit Test`


## Note:
Keys in this project are not unique, non-unique key insertions can break your code if youre not careful.
However handling non-unique keys can produce different tree structures that are all valid (More precisely, it depends which root node is assigned to be the child of the other root node with the same rank and key), And therefore I'm unable to test such scenarios uniformly for everyone. but feel free to add more tests yourself, the syntax is relatively simple and can be deduced immediately from current tests.




