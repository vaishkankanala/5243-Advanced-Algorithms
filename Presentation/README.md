# 📚 Trie Data Structure Quiz

Test your knowledge of Trie data structures with these multiple-choice questions. Each question includes detailed explanations to help reinforce key concepts.

## 🧠 Quiz Questions

### 1. What is a key advantage of using a Compressed Trie over a Standard Trie?
**Options:**  
🔘 A) Allows storing numbers more easily  
✅ B) Reduces space by collapsing single-child paths *(Correct)*  
🔘 C) Improves sorting speed of strings  
🔘 D) Increases time complexity for lookup  

**💡 Explanation:**  
Compressed Tries optimize storage by merging nodes that have only one child, significantly reducing space usage compared to Standard Tries where each character gets its own node.

---

### 2. What is the average time complexity for searching a word in a standard Trie? (L = length of word)
**Options:**  
🔘 A) O(log L)  
🔘 B) O(L²)  
✅ C) O(L) *(Correct)*  
🔘 D) O(L log L)  

**💡 Explanation:**  
Tries provide constant-time access per character, making search operations linear relative to the length of the input word (O(L)).

---

### 3. Which of the following is a primary use of Suffix Trie?
**Options:**  
🔘 A) Prefix matching  
🔘 B) Word counting  
✅ C) Pattern Matching *(Correct)*  
🔘 D) Binary search  

**💡 Explanation:**  
Suffix Tries excel at substring searches because they preprocess all possible suffixes of a string, enabling efficient pattern matching.

---

### 4. Which of the following is a common real-world application of a Trie data structure?
**Options:**  
🔘 A) Image compression  
🔘 B) Graph traversal  
✅ C) Autocomplete in search engines *(Correct)*  
🔘 D) Sorting integers in an array  

**💡 Explanation:**  
Tries are particularly useful for text-based operations like autocomplete, as they can quickly find all words with a given prefix.

