# Java Vote Consolidator Exercise 

This is a basic Java repository created for training and practicing fundamental programming concepts. The program reads election logs from a `.csv` file and generates a consolidated report displaying the total votes for each candidate.

---

##  Objective
The goal of this project is to read a text file containing candidate names and vote counts per voting machine (ballot box). The program aggregates the data, ensuring no candidate names are duplicated, and sums up the total votes for each candidate using key-value pair structures.

---

##  Concepts Practiced
* **File Manipulation:** Implementing `BufferedReader` and `FileReader` for efficient stream reading.
* **Java Collections Framework:** Using the `Map` interface (`LinkedHashMap`) to store unique keys (candidate names) and handle values (vote accumulation).
* **Exception Handling:** Managing input/output errors with `try-catch` blocks and `IOException`.
* **Loops and Logic:** Iterating through structures using `.keySet()` and conditional checks (`containsKey`) to merge counts.

---

##  How It Works

### Input File Example (`.txt` or `.csv`)
```text
Alex Blue,15
Maria Green,22
Bob Brown,21
Alex Blue,30
Bob Brown,15
