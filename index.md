---
layout: default
title: Behind The Click
description: >
  Dive into the logic that powers every Google product—uncovering the data structures and algorithms shaping user experiences.
---

> 🧠 “Every tap on a Google service triggers a chain of finely-tuned algorithms — it’s time to uncover what clicks behind the click.”

Welcome to **Behind The Click** — a curated exploration of the **algorithmic blueprints** driving Google's smartest features.

From the instant results of Search to the route optimizations in Maps, this portfolio connects everyday experiences with the **data structures and algorithms** behind them. It's not just about theory — it's about **understanding how real-world systems are built**.

Whether you're intrigued by how a Trie enables Autocomplete or how Segment Trees avoid calendar overlaps, this collection bridges intuition with implementation in the most engaging way.

---

## 📌 Details

<dl>
  <dt><strong>Name</strong></dt>
  <dd>Shradha S. Kekare</dd>

  <dt><strong>USN</strong></dt>
  <dd>01fe22bcs263</dd>

  <dt><strong>Course Name</strong></dt>
  <dd>Algorithmic Problem Solving</dd>

  <dt><strong>Domain</strong></dt>
  <dd>Google Services</dd>

  <dt><strong>Course Code</strong></dt>
  <dd>23ECSE304</dd>

  <dt><strong>Faculty</strong></dt>
  <dd>Prakash Hegade</dd>

  <dt><strong>University</strong></dt>
  <dd>KLE Technological University, Hubballi-31</dd>
</dl>

<p align="center">
  <img src="images/google.png" alt="Google Logo" width="400">
</p>

---

## Google Services & Algorithms

Explore how Google integrates powerful algorithms behind its core services. This timeline-style format outlines how each service operates step by step, highlighting the algorithms that make them fast, scalable, and intelligent.



### 🔍 Google Search – From Query to Result

1. **User enters a search query**  
   → The query is matched using **Rabin-Karp** and **KMP** string matching algorithms.  
   📄 [Details](1.html)  
   

2. **Autocomplete suggestions appear**  
   → Generated in real-time using **Trie** and **Ternary Search Trees**.  
   📄 [Details](2.html)  
   

3. **Relevant pages are ranked**  
   → Ranked by importance using **PageRank**, **DFS**, and **BFS** over the link graph.  
   📄 [Details](3.html)  
   

4. **Frequently accessed results are cached**  
   → Handled by **LRU**, **LFU**, and **HashMap + DLL** based caches.  
   📄 [Details](4.html)  
   
5. **Spelling mistakes are corrected**  
   → Corrected using **Levenshtein Distance** and **Trigram Matching**.  
   📄 [Details](5.html)  
  
---

### 🗺️ Google Maps – Navigating the Real World

1. **User requests directions**  
   → Shortest paths computed using **Dijkstra's**, **A\* Search**, or **Bellman-Ford**.  
   📄 [Details](6.html)  
   

2. **Live traffic is analyzed**  
   → Traffic estimates made using **Dynamic Graphs**, **Real-time A\***, and **Floyd-Warshall**.  
   📄 [Details](7.html)  
   
3. **Nearby places are grouped**  
   → Clustered using **Union-Find**, **DBSCAN**, or **K-Means** algorithms.  
   📄 [Details](8.html)  
  

4. **Regional boundaries are analyzed**  
   → Handled with **Convex Hull (Graham Scan)** and **K-D Trees** for spatial mapping.  
   📄 [Details](9.html)  
   

---

### 📧 Gmail – Smarter Email Management

1. **Emails are grouped into threads**  
   → Achieved with **Union-Find**, **Disjoint Sets**, and **Hash Maps**.  
   📄 [Details](10.html)  
   

2. **Frequently viewed emails are cached**  
   → Managed using **LRU**, **LFU**, and **ARC** caching strategies.  
   📄 [Details](11.html)  
   

3. **Attachments are compressed**  
   → Compressed efficiently using **Huffman Coding**.  
   📄 [Details](12.html)  
   

4. **Search across mailbox is performed**  
   → Uses **Inverted Index** for fast keyword lookup.  
   📄 [Details](13.html)  
   

---

### 📺 YouTube – Organizing the Video World

1. **Videos are indexed**  
   → Structured using **Suffix Trees** and **Inverted Index** to support fast retrieval.  
   📄 [Details](14.html)  
   
2. **Users search for videos**  
   → Matches video metadata using **Suffix Arrays** and **KMP** pattern matching.  
   📄 [Details](15.html)  
   
3. **Trending content is detected**  
   → Tracked using **Sliding Window** techniques and **Heap-based Counters**.  
   📄 [Details](16.html)  
   

4. **Videos are compressed for storage**  
   → Uses **Huffman Coding**, **Arithmetic Coding**, and **Run-Length Encoding**.  
   📄 [Details](17.html)  
  
---

### 📆 Google Calendar – Scheduling Smarter

1. **Event is created and stored**  
   → Events are sorted using **Merge Sort**, **Quick Sort**, or **Heap Sort**.  
   📄 [Details](18.html)  
   

2. **System checks for availability**  
   → Uses **Binary Search**, **Sparse Tables**, or **Segment Trees** to avoid overlaps.  
   📄 [Details](19.html)  
   

3. **Reminder is set for the user**  
   → Managed using **Priority Queues**, **Min-Heaps**, or **Time Wheels** for timely alerts.  
   📄 [Details](20.html)  
  

4. **Recurring events are managed**  
   → Efficiently tracked with **Linked Lists**, **Hash Maps**, and **Cycle Detection (Floyd’s Algorithm)** for repeating schedules.  
   📄 [Details](21.html)  
  

---

### 📸 Google Photos – Organizing Memories with Intelligence

1. **🗑️ Duplicate photos are detected and removed**  
   → Leveraging **Hash Tables** for quick image hashing, **Bloom Filters** for space-efficient duplicate checks, and **Hamming Distance** for perceptual similarity detection.  
   📄 [Details](22.html)  
  

2. **🗂️ Albums are created automatically**  
   → Clustered using **K-Means** and **DBSCAN**, guided by **Cosine Similarity** and **metadata trees** (e.g., date → location → tag) to group related photos.  
   📄 [Details](23.html)  
   
3. **🕒 Timeline view is arranged by date**  
   → Efficiently sorted using **Radix Sort** and **Bucket Sort** for date fields, or using **Custom Comparators** in **Balanced BSTs** or **Min-Heaps**.  
   📄 [Details](24.html)  
   

4. **👥 Face grouping across photos**  
   → Constructed as a graph problem: nodes represent faces, edges represent similarity; solved using **Disjoint Set Union (DSU)** for grouping, **Euclidean Distance** for similarity, and **Connected Components** detection in **Adjacency Lists**.  
   📄 [Details](25.html)  
 


## References

- [GeeksforGeeks](https://www.geeksforgeeks.org/)  
- Wikipedia: Dijkstra, Trie, Hashing  
- Stack Overflow Discussions

> 📌 This  portfolio outlines the key **Data Structures and Algorithms (DSA)** behind Google’s services, providing insight into real-world applications of theoretical concepts.

