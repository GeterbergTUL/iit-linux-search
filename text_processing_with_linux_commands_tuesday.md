> This is the demonstration how to use Linux commands to process strutured text data.

### 0. How many lines are in fullnames_with_age.txt?

Put screenshot from Codespaces illustrating the result here.
Correct screenshot should contain your github username in the shell, a command and the result.

Example:

![task 0](task0.png)

**Explanation** Write the explanation why the specific command was used.

Example: wc command is to count data in a given file. -l parameter is for counting lines.

### 1. How many lines in access_small.log have path /login?

![alt text](image.png)

**Explanation** Write the explanation why the specific command was used.

grep is used to select only the lines containing "/login", wc -l counts the line after filtering
---

### 2. How many different ages are in fullnames_with_age.txt?

![alt text](image-1.png)

**Explanation** Write the explanation why the specific command was used.

cut is used to only get the numbers at the end of each line (after =), sort and later uniq ensure that there is only one occurance of a number is left, then wc -l counts the lines
---

### 3. How many unique first names are in fullnames_with_age.txt?

![alt text](image-2.png)

**Explanation** Write the explanation why the specific command was used.

Same as in previous question but we access the first names by selecting the first column while dividing with spaces
---

### 4. Which age is most frequent in fullnames_with_age.txt?

![alt text](image-3.png)

**Explanation** Write the explanation why the specific command was used.

We once again extract only the ages and sort them but we count the occurances while filtering out the duplicates. Then we sort again with reverse order to see the most common occurance (56) on top - for convenience
---

### 5. Which username failed login most often in auth_small.csv?

![alt text](image-4.png)

**Explanation** Write the explanation why the specific command was used.

First we filter only the lines with fail, we isolate the usernames, we count occurances after sorting, we sort again for convenience - most common fail is dave
---

### 6. How many lines in system_small.log have ok=true?

![alt text](image-5.png)

**Explanation** Write the explanation why the specific command was used.

We select only the lines with "ok=true" and count the lines
---

### 7, Which level (INFO, WARN, ERROR) appears most often in system_small.log?

Put screenshot from Codespaces illustrating the result here.
Correct screenshot should contain your github username in the shell, a command and the result.

**Explanation** Write the explanation why the specific command was used.

---

### 8. What is the top 3 most common actions in app_small.log?

Put screenshot from Codespaces illustrating the result here.
Correct screenshot should contain your github username in the shell, a command and the result.

**Explanation** Write the explanation why the specific command was used.

---

### 9. How many unique users are in app_small.log?

Put screenshot from Codespaces illustrating the result here.
Correct screenshot should contain your github username in the shell, a command and the result.

**Explanation** Write the explanation why the specific command was used.

---