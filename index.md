---
layout: default
title: Behind The Click
description: >
  Revealing the code and logic behind every Google click and experience.


  
---


> 🧠 "Behind every seamless Google experience lies a carefully crafted algorithm."

Welcome to **Behind The Click** – a deep dive into the **algorithmic engines** powering Google’s most iconic services.

Explore how classical and modern **Data Structures and Algorithms (DSA)** bring intelligence, scalability, and lightning speed to platforms like Search, Maps, Gmail, and YouTube.

Whether you're curious about how a Trie powers Autocomplete or how PageRank works behind search results – this portfolio makes it all accessible, meaningful, and connected to reality.


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


## Google Services & Algorithms

Explore how Google integrates powerful algorithms behind its core services. This timeline-style format outlines how each service operates step by step, highlighting the algorithms that make them fast, scalable, and intelligent.

### 🔍 Google Search – From Query to Result

1. **User enters a search query**  
   → The query is matched using **Rabin-Karp** and **KMP** string matching algorithms.  
   📄 [Details](1.html)  
   🎞️ **Watch It Work**  
   ![](images/search_string_match.gif)

2. **Autocomplete suggestions appear**  
   → Generated in real-time using **Trie** and **Ternary Search Trees**.  
   📄 [Details](2.html)  
   🎞️ **Watch It Work**  
   ![](images/autocomplete_trie.gif)

3. **Relevant pages are ranked**  
   → Ranked by importance using **PageRank**, **DFS**, and **BFS** over the link graph.  
   📄 [Details](3.html)  
   🎞️ **Watch It Work**  
   ![](images/page_rank_graph.gif)

4. **Frequently accessed results are cached**  
   → Handled by **LRU**, **LFU**, and **HashMap + DLL** based caches.  
   📄 [Details](4.html)  
   🎞️ **Watch It Work**  
   ![](images/cache_lru.gif)

5. **Spelling mistakes are corrected**  
   → Corrected using **Levenshtein Distance** and **Trigram Matching**.  
   📄 [Details](5.html)  
   🎞️ **Watch It Work**  
   ![](images/spell_check_edit_distance.gif)

---

### 🗺️ Google Maps – Navigating the Real World

1. **User requests directions**  
   → Shortest paths computed using **Dijkstra's**, **A\* Search**, or **Bellman-Ford**.  
   📄 [Details](6.html)  
   🎞️ **Watch It Work**  
   ![](images/maps_pathfinding.gif)

2. **Live traffic is analyzed**  
   → Traffic estimates made using **Dynamic Graphs**, **Real-time A\***, and **Floyd-Warshall**.  
   📄 [Details](7.html)  
   🎞️ **Watch It Work**  
   ![](images/traffic_dynamic_graph.gif)

3. **Nearby places are grouped**  
   → Clustered using **Union-Find**, **DBSCAN**, or **K-Means** algorithms.  
   📄 [Details](8.html)  
   🎞️ **Watch It Work**  
   ![](images/clustering_kmeans.gif)

4. **Regional boundaries are analyzed**  
   → Handled with **Convex Hull (Graham Scan)** and **K-D Trees** for spatial mapping.  
   📄 [Details](9.html)  
   🎞️ **Watch It Work**  
   ![](images/convex_hull.gif)

---

### 📧 Gmail – Smarter Email Management

1. **Emails are grouped into threads**  
   → Achieved with **Union-Find**, **Disjoint Sets**, and **Hash Maps**.  
   📄 [Details](10.html)  
   🎞️ **Watch It Work**  
   ![](images/email_union_find.gif)

2. **Frequently viewed emails are cached**  
   → Managed using **LRU**, **LFU**, and **ARC** caching strategies.  
   📄 [Details](11.html)  
   🎞️ **Watch It Work**  
   ![](images/email_cache_arc.gif)

3. **Attachments are compressed**  
   → Compressed efficiently using **Huffman Coding**.  
   📄 [Details](12.html)  
   🎞️ **Watch It Work**  
   ![](images/huffman_coding.gif)

4. **Search across mailbox is performed**  
   → Uses **Inverted Index** for fast keyword lookup.  
   📄 [Details](13.html)  
   🎞️ **Watch It Work**  
   ![](images/inverted_index.gif)

---

### 📺 YouTube – Organizing the Video World

1. **Videos are indexed**  
   → Structured using **Suffix Trees** and **Inverted Index** to support fast retrieval.  
   📄 [Details](14.html)  
   🎞️ **Watch It Work**  
   ![](images/suffix_tree.gif)

2. **Users search for videos**  
   → Matches video metadata using **Suffix Arrays** and **KMP** pattern matching.  
   📄 [Details](15.html)  
   🎞️ **Watch It Work**  
   ![](images/suffix_array_kmp.gif)

3. **Trending content is detected**  
   → Tracked using **Sliding Window** techniques and **Heap-based Counters**.  
   📄 [Details](16.html)  
   🎞️ **Watch It Work**  
   ![](images/trending_sliding_window.gif)

4. **Videos are compressed for storage**  
   → Uses **Huffman Coding**, **Arithmetic Coding**, and **Run-Length Encoding**.  
   📄 [Details](17.html)  
   🎞️ **Watch It Work**  
   ![](images/video_compression.gif)

---

### 📆 Google Calendar – Scheduling Smarter

1. **Event is created and stored**  
   → Events are sorted using **Merge Sort**, **Quick Sort**, or **Heap Sort**.  
   📄 [Details](18.html)  
   🎞️ **Watch It Work**  
   ![](images/calendar_sorting.gif)

2. **System checks for availability**  
   → Uses **Binary Search**, **Sparse Tables**, or **Segment Trees** to avoid overlaps.  
   📄 [Details](19.html)  
   🎞️ **Watch It Work**  
   ![](images/availability_segment_tree.gif)

3. **Reminder is set for the user**  
   → Managed using **Priority Queues**, **Min-Heaps**, or **Time Wheels** for timely alerts.  
   📄 [Details](20.html)  
   🎞️ **Watch It Work**  
   ![](images/reminder_priority_queue.gif)

4. **Recurring events are managed**  
   → Efficiently tracked with **Linked Lists**, **Hash Maps**, and **Cycle Detection (Floyd’s Algorithm)** for repeating schedules.  
   📄 [Details](21.html)  
   🎞️ **Watch It Work**  
   ![](images/recurring_events.gif)

---

### 📸 Google Photos – Organizing Memories with Intelligence

1. **Duplicate photos are detected and removed**  
   → Using **Hashing**, **Bloom Filters**, and **Hamming Distance** for image fingerprinting.  
   📄 [Details](22.html)  
   🎞️ **Watch It Work**  
   ![](images/photo_deduplication.gif)

2. **Albums are created automatically**  
   → Clustered with **K-Means**, **DBSCAN**, and **Cosine Similarity** on metadata + timestamps.  
   📄 [Details](23.html)  
   🎞️ **Watch It Work**  
   ![](images/auto_album_clustering.gif)

3. **Timeline view is arranged by date**  
   → Organized using **Radix Sort**, **Bucket Sort**, or **Custom Comparators**.  
   📄 [Details](24.html)  
   🎞️ **Watch It Work**  
   ![](images/timeline_sorting.gif)

4. **Face grouping across photos**  
   → Performed using **Disjoint Set Union (DSU)**, **Euclidean Distance**, and **Graph Components**.  
   📄 [Details](25.html)  
   🎞️ **Watch It Work**  
   ![](images/face_grouping_dsu.gif)


## References

- [GeeksforGeeks](https://www.geeksforgeeks.org/)  
- Wikipedia: Dijkstra, Trie, Hashing  
- Stack Overflow Discussions

> 📌 This  portfolio outlines the key **Data Structures and Algorithms (DSA)** behind Google’s services, providing insight into real-world applications of theoretical concepts.

