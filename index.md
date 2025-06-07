---
layout: default
title: Behind The Click
description: >
  Dive into the logic that powers every Google product—uncovering the data structures and algorithms shaping user experiences.
---

<p style="font-size: 1.1rem; font-style: italic; color: #555;">
  🧠 “Every tap on a Google service triggers a chain of finely-tuned algorithms — it’s time to uncover what clicks behind the click.”
</p>




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



### 🧪 Case Study: How Google Search Delivers the Perfect Result

#### 🔍 Scenario: A User Searches for "Best DSLR Cameras"

> On a regular morning, a user types "Best DSLR Cameras for Beginners" into Google. Within milliseconds, Google presents hundreds of relevant, ranked, and refined results. But what’s happening behind the scenes?

---

#### 🛠️ Step 1: String Matching Begins

To match the query to documents, **Rabin-Karp** and **KMP** algorithms are applied for efficient pattern searching across billions of indexed web pages.  
📄 [Details](1.html)

- 📌 **Why KMP/Rabin-Karp?**  
  These algorithms offer fast and scalable substring matching by avoiding re-checking characters.

---

#### 🧠 Step 2: Autocomplete Kicks In

Before the user even finishes typing, suggestions like *"Best DSLR Cameras 2025"* pop up—thanks to **Trie** and **Ternary Search Trees** enabling prefix-based lookups in real-time.  
📄 [Details](2.html)

- 📌 **Why Tries?**  
  Tries reduce lookup time to O(L), where L is the length of the prefix.

---

#### 📈 Step 3: Page Ranking Magic

Once results are fetched, they’re sorted using **PageRank**, combined with **DFS** and **BFS** to traverse the web’s graph of interconnected pages.  
📄 [Details](3.html)

- 📌 **Why Graph Algorithms?**  
  They help evaluate importance based on the number and quality of inbound links.

---

#### 💾 Step 4: Caching for Speed

Frequently visited search results are retrieved from **LRU**, **LFU**, or **HashMap + DLL** caches, improving speed and reducing recomputation.  
📄 [Details](4.html)

- 📌 **Why Caching?**  
  To serve common queries in constant time.

---

#### 📝 Step 5: Handling Typos

If the user accidentally types "Best DSLF Cameraz", Google's spell checker steps in using **Levenshtein Distance** and **Trigram Matching** to suggest "Best DSLR Cameras".  
📄 [Details](5.html)

- 📌 **Why Edit Distance?**  
  It helps find the most likely intended query based on minimal edits.

---

#### ✅ Final Outcome:

In under 0.3 seconds, the user sees:
- Accurate search results  
- Helpful auto-suggestions  
- Corrected spellings  
- Fast load times due to caching  



---

> 🔎 **Summary**: Google Search isn’t just a black box—it’s a beautifully choreographed system where **graphs**, **tries**, **DP**, and **greedy logic** blend to serve billions daily.




### 🧪 Case Study: How Google Maps Gets You There (Fast)

#### 🗺️ Scenario: A User Navigates to a Café in Traffic in Hubballi

> It’s a busy Monday. A user opens Google Maps and searches for the quickest route to their favorite café. Maps instantly shows directions, live traffic, and nearby recommendations. But what powers this magic?

---

#### 🧭 Step 1: Finding the Shortest Path

As soon as the destination is selected, Google Maps computes the **fastest route** using algorithms like **Dijkstra’s**, **A\***, and **Bellman-Ford**.  
📄 [Details](6.html)

- 📌 **Why These Algorithms?**  
  - **Dijkstra’s**: Efficient for positive-weight roads.  
  - **A\***: Adds heuristics for faster routing.  
  - **Bellman-Ford**: Handles graphs with negative weights (less common, but useful in traffic prediction).

---

#### 🚦 Step 2: Live Traffic Integration

While calculating the route, Maps considers **real-time congestion** using **Dynamic Graphs** and **Real-Time A\*** updates.  
📄 [Details](7.html)

- 📌 **How It Works:**  
  - Traffic updates change edge weights dynamically.  
  - **Floyd-Warshall** helps in static all-pairs path precomputation for quick rerouting.

---

#### 🗃️ Step 3: Grouping Nearby Places

Looking for coffee shops or ATMs nearby? Maps uses **clustering** to group similar points of interest.  
📄 [Details](8.html)

- 🧠 Algorithms at Play:  
  - **Union-Find (DSU)**: For spatial grouping.  
  - **DBSCAN**: Density-based clustering (no need to predefine clusters).  
  - **K-Means**: Location-based grouping.

---

#### 📍 Step 4: Regional Mapping and Boundaries

Zooming in shows neighborhood outlines, park boundaries, or lake contours—crafted using **Convex Hull** and **K-D Trees**.  
📄 [Details](9.html)

- 📌 **Why These Structures?**  
  - **Convex Hull (Graham Scan)** outlines the outer boundary of locations.  
  - **K-D Trees** enable fast spatial queries like "Find the 5 nearest places".

---

#### ✅ Final Outcome:

Within seconds, the user gets:
- Optimal route suggestions  
- Real-time traffic-aware updates  
- Grouped POIs for discovery  
- Seamless regional map overlays  

All thanks to the smart use of **DSA-powered algorithms** that bring intelligence to navigation.

---
> 🔎 **Summary**: Google Maps uses classic graph algorithms, clustering techniques, and spatial data structures to deliver real-time, intelligent navigation experiences.4
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

