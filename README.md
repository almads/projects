**README for Call to Order and The Infinite Monkey Theorem Projects**

**Project 3: Call to Order**

**Overview:**
The "Call to Order" project is focused on extending an ArrayList-like class to support sorting, specifically tailored for managing Bowdoin College student directory information. The project aims to provide hands-on experience with inheritance, interfaces, String methods, comparators, and generics, along with exploring the implementation of inner classes.

**Learning Goals:**
- Extend an ArrayList-like class to support sorting
- Gain experience with inheritance, interfaces, String methods, comparators, and generics
- Explore the implementation of inner classes

**Specifications:**
The project involves creating three classes:
1. **SortableArrayList:** A class supporting sorting, extending from a SimpleArrayList class, provided but not to be modified.
2. **Student:** Represents a single student’s information read from a Bowdoin College directory file.
3. **DirectorySort:** Acts as a holder for the main method and any helper methods, responsible for reading the directory file, constructing a list of Student objects, and sorting it based on various criteria.

**Implementation:**
- **SortableArrayList:** Inherits from SimpleArrayList and implements sorting methods using selection sort algorithm.
- **Student:** Represents student information parsed from the directory file.
- **DirectorySort:** Utilizes SortableArrayList to sort Student objects based on various criteria, including SU box, last name, vowels in the name, and occurrences of a digit in the phone number.

**Testing:**
The functionality of sorting and directory analysis can be tested by running the main method in DirectorySort, which includes test cases for various sorting criteria.

**Project 2: The Infinite Monkey Theorem**

**Overview:**
The "Infinite Monkey Theorem" project simulates a "somewhat clever" monkey attempting to write text resembling works of famous authors by mimicking patterns observed in sample texts. The algorithm used involves analyzing character probability distributions to generate random text that resembles the input text.

**Learning Goals:**
- Understand character probability distributions
- Implement text generation based on probability analysis
- Gain experience with file I/O in Java

**Implementation:**
The implementation involves analyzing input text files to determine character probability distributions at different levels (up to a specified depth). The program then generates random text by selecting characters based on the observed probabilities.

**Specifications:**
- Prompt the user to enter the name of an input file and the desired depth of analysis (k).
- Analyze the input text to determine character probability distributions at the specified depth.
- Generate random text following the observed probabilities.
- Output 500 characters of randomly generated text based on the input analysis.

**Testing:**
The program can be tested by providing input text files of various lengths and complexities to observe how accurately the generated text resembles the original. Additionally, testing can ensure proper functionality of file I/O and error handling for invalid inputs.

**Note:**
Both projects offer valuable opportunities to practice core Java concepts and algorithms while addressing specific problem domains. The README provides a brief overview of each project's objectives, implementation details, and testing strategies to guide users in understanding and utilizing the provided code effectively.
