---
layout: default
title: Behind The Click
---

> 🧠 "Behind every seamless Google experience lies a carefully crafted algorithm."

Welcome to **Behind The Click** – a deep dive into the **algorithmic engines** powering Google’s most iconic services.

Explore how classical and modern **Data Structures and Algorithms (DSA)** bring intelligence, scalability, and lightning speed to platforms like Search, Maps, Gmail, and YouTube.

Whether you're curious about how a Trie powers Autocomplete or how PageRank works behind search results – this portfolio makes it all accessible, meaningful, and connected to reality.

---

## 🔗 Table of Contents

- [📌 Details](#-details)
- [🎯 Motivation](#-motivation)
- [🚀 Objectives](#-objectives)
- [🧮 Google Services & Algorithms](#google-services--algorithms)
- [📚 References](#references)

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


## 🎯 Motivation

> Why Google? Why Algorithms?

With billions of users relying on Google every day, it's fascinating to understand how **intelligent algorithmic strategies** drive performance. This portfolio was inspired by a desire to bridge academic knowledge of **DSA** with **real-world services** we use daily.

---

## 🚀 Objectives

- 🔍 Identify and explore core Google services.
- 🔧 Highlight algorithms behind each functionality.
- 📊 Explain how those algorithms work, and why they’re efficient.
- 🌍 Link every algorithm to its real-world context.

---

## Google Services & Algorithms

Explore how Google integrates powerful algorithms behind its core services. This timeline-style format outlines how each service operates step by step, highlighting the algorithms that make them fast, scalable, and intelligent.


### 🔍 Google Search – From Query to Result

<details open>
<summary>1. 🧠 Query Matching using Rabin-Karp & KMP</summary>

- ✏️ **What happens**: User enters a search query.
- 🔍 **How it works**: The query is matched using **Rabin-Karp** and **KMP**.
- 🎞️ **Watch it work**:  
  ![Rabin-Karp vs KMP](images/rk_kmp.gif) <!-- Your GIF here -->
- 📄 [See Code + Explanation](1.html)
</details>



<details>
<summary>2. ⚡ Autocomplete via Trie & TST</summary>

- ✏️ **What happens**: Autocomplete suggestions appear while typing.
- 🧠 **How it works**: Uses **Trie** and **Ternary Search Trees** for prefix matching.
- 🎞️ **Watch it work**:  
  ![Autocomplete Trie](images/trie_autocomplete.gif)
- 📄 [See Code + Explanation](2.html)
</details>



<details>
<summary>3. 📈 Ranking with PageRank, DFS & BFS</summary>

- ✏️ **What happens**: Relevant pages are ranked.
- 🧠 **How it works**: **PageRank**, **DFS**, and **BFS** traverse the link graph to rank pages.
- 🎞️ **Watch it work**:   
  ![PageRank Visualization](images/pagerank.gif)
- 📄 [See Code + Explanation](3.html)
</details>



<details>
<summary>4. 🗂️ Caching with LRU, LFU, HashMap + DLL</summary>

- ✏️ **What happens**: Frequently accessed results are cached.
- 🧠 **How it works**: Uses **LRU**, **LFU**, and **HashMap + DLL** for quick lookups.
- 🎞️ **Watch it work**:  
  ![LRU Cache Demo](images/lru_cache.gif)
- 📄 [See Code + Explanation](4.html)
</details>



<details>
<summary>5. ✨ Spell Correction using Levenshtein & Trigrams</summary>

- ✏️ **What happens**: Misspelled queries are auto-corrected.
- 🧠 **How it works**: Uses **Levenshtein Distance** to find closest valid words, **Trigrams** to rank them.
- 🎞️ **Watch it work**:  
  ![Levenshtein Demo](images/levenshtein.gif)
- 📄 [See Code + Explanation](5.html)
</details>

---

## 🗺️ Google Maps – Navigating the Real World

<details open>
<summary>1. 🚗 Route Finding with Dijkstra, A*, Bellman-Ford</summary>

- ✏️ **What happens**: User requests directions.
- 🧠 **How it works**: Computes shortest path using **Dijkstra’s**, **A\***, or **Bellman-Ford**.
- 🎞️ **Watch it work**:  

  ![Dijkstra Path](images/dijkstra_map.gif)
- 📄 [Details](6.html)
</details>

<details>
<summary>2. 🚦 Live Traffic Analysis with Real-time Algorithms</summary>

- ✏️ **What happens**: Traffic conditions influence route choices.
- 🧠 **How it works**: Uses **Dynamic Graphs**, **Real-time A\***, and **Floyd-Warshall** for adjustments.
- 🎞️ **Watch it work**:  
   
  ![Traffic GIF](images/traffic_analysis.gif)
- 📄 [Details](7.html)
</details>

<details>
<summary>3. 📍 Clustering Nearby Places</summary>

- ✏️ **What happens**: Nearby places are grouped.
- 🧠 **How it works**: Clustering with **Union-Find**, **DBSCAN**, or **K-Means**.
- 🎞️ **Watch it work**:  
  _Animated GIF showing nearby points being grouped into clusters._  
  ![Clustering GIF](images/nearby_cluster.gif)
- 📄 [Details](8.html)
</details>

<details>
<summary>4. 🗺️ Spatial Mapping with Convex Hull & K-D Trees</summary>

- ✏️ **What happens**: Regional boundaries are computed.
- 🧠 **How it works**: Uses **Convex Hull (Graham Scan)** and **K-D Trees**.
- 🎞️ **Watch it work**:  
  _GIF showing region boundaries forming around geo-points._  
  ![Convex Hull GIF](images/convex_kdtree.gif)
- 📄 [Details](9.html)
</details>

---

## 📧 Gmail – Smarter Email Management

<details open>
<summary>1. 🧵 Threading Emails with Union-Find</summary>

- ✏️ **What happens**: Emails are grouped into threads.
- 🧠 **How it works**: Uses **Disjoint Sets**, **Union-Find**, and **Hash Maps**.
- 🎞️ **Watch it work**:  
  
  ![Email Thread GIF](images/email_thread.gif)
- 📄 [Details](10.html)
</details>

<details>
<summary>2. 💾 Caching Frequently Accessed Emails</summary>

- ✏️ **What happens**: Frequently opened emails are cached.
- 🧠 **How it works**: Caching via **LRU**, **LFU**, and **ARC** strategies.
- 🎞️ **Watch it Work**:  
 
  ![Email Cache GIF](images/email_cache.gif)
- 📄 [Details](11.html)
</details>

<details>
<summary>3. 📎 Compressing Attachments with Huffman Coding</summary>

- ✏️ **What happens**: Attachments are compressed for storage.
- 🧠 **How it works**: Compression using **Huffman Coding**.
- 🎞️ **Watch it work**:  

  ![Huffman GIF](images/huffman_compression.gif)
- 📄 [Details](12.html)
</details>

<details>
<summary>4. 🔎 Fast Mail Search with Inverted Index</summary>

- ✏️ **What happens**: Searching across your inbox.
- 🧠 **How it works**: Uses an **Inverted Index** for fast keyword lookups.
- 🎞️ **Watch it work**:  

  ![Inverted Index GIF](images/inverted_index.gif)
- 📄 [Details](13.html)
</details>

---

## 📺 YouTube – Organizing the Video World

<details open>
<summary>1. 🗂️ Video Indexing using Suffix Trees</summary>

- ✏️ **What happens**: Videos are indexed for search and recommendations.
- 🧠 **How it works**: Structures like **Suffix Trees** and **Inverted Index** are used.
- 🎞️ **Watchit work**:  

  ![Suffix Tree GIF](images/suffix_tree.gif)
- 📄 [Details](14.html)
</details>

<details>
<summary>2. 🔍 Metadata Search using Suffix Arrays & KMP</summary>

- ✏️ **What happens**: User searches for videos.
- 🧠 **How it works**: Matches metadata using **Suffix Arrays** and **KMP**.
- 🎞️ **Watch it work**:  

  ![KMP Metadata GIF](images/kmp_suffix.gif)
- 📄 [Details](15.html)
</details>

<details>
<summary>3. 📊 Detecting Trends via Sliding Window</summary>

- ✏️ **What happens**: Trending content is surfaced.
- 🧠 **How it works**: Detected with **Sliding Window** and **Heap Counters**.
- 🎞️ **Watch it work**:  

  ![Trending Detection GIF](images/trending_window.gif)
- 📄 [Details](16.html)
</details>

<details>
<summary>4. 🗜️ Video Compression Techniques</summary>

- ✏️ **What happens**: Videos are compressed for storage efficiency.
- 🧠 **How it works**: Uses **Huffman**, **Arithmetic**, and **Run-Length Encoding**.
- 🎞️ **Watch it work**:  
  
  ![Video Compression GIF](images/video_compress.gif)
- 📄 [Details](17.html)
</details>

---

## 📆 Google Calendar – Scheduling Smarter

<details open>
<summary>1. 🗓️ Event Sorting with Classic Sort Algorithms</summary>

- ✏️ **What happens**: Events are sorted chronologically.
- 🧠 **How it works**: Uses **Merge Sort**, **Quick Sort**, or **Heap Sort**.
- 🎞️ **Watch it work**:  
 
  ![Sort Events GIF](images/calendar_sort.gif)
- 📄 [Details](18.html)
</details>

<details>
<summary>2. ⏳ Availability Checking via Interval Search</summary>

- ✏️ **What happens**: System checks for free time slots.
- 🧠 **How it works**: Uses **Binary Search**, **Sparse Tables**, and **Segment Trees**.
- 🎞️ **Watch it work**:  

  ![Calendar Search GIF](images/calendar_check.gif)
- 📄 [Details](19.html)
</details>

<details>
<summary>3. ⏰ Reminders via Priority Queues</summary>

- ✏️ **What happens**: Reminders pop up before events.
- 🧠 **How it works**: Uses **Priority Queues**, **Min-Heaps**, and **Time Wheels**.
- 🎞️ **Watch it work**:  

  ![Reminder Queue GIF](images/reminder_heap.gif)
- 📄 [Details](20.html)
</details>

---

## References

- [GeeksforGeeks](https://www.geeksforgeeks.org/)  
- Wikipedia: Dijkstra, Trie, Hashing  
- Stack Overflow Discussions

> 📌 This  portfolio outlines the key **Data Structures and Algorithms (DSA)** behind Google’s services, providing insight into real-world applications of theoretical concepts.

