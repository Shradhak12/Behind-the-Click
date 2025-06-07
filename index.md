---
layout: default
title: Behind The Click
description: >
  Dive into the logic that powers every Google product—uncovering the data structures and algorithms shaping user experiences.
---

<p style="font-size: 1.4rem; font-weight: bold; font-style: italic; color: #333; text-align: center;">
  🧠 “Every tap on a Google service triggers a chain of finely-tuned algorithms — it’s time to uncover what clicks behind the click.”
</p>

**Welcome to Behind The Click — a curated exploration of the algorithmic blueprints driving Google's smartest features.**

**From the instant results of Search to the route optimizations in Maps, this portfolio connects everyday experiences with the data structures and algorithms behind them. It's not just about theory — it's about understanding how real-world systems are built.**

---

# 📌 Details

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

# 🚀 Google Services & Algorithms

Explore how Google integrates powerful algorithms behind its core services. This timeline-style format outlines how each service operates step by step, highlighting the algorithms that make them fast, scalable, and intelligent.

---

# 🌟 A Day in the Googleverse — The Story

> It starts with a search. A curious morning thought leads you to Google. That one phrase — typed in seconds — triggers trillions of instructions. From instant recommendations in YouTube to live traffic updates on Maps, Google becomes your silent co-pilot.  
>  
> As the day unfolds, you swipe through old photos, respond to a Calendar notification, and take a shortcut thanks to Maps’ clever rerouting. It feels seamless. But behind every feature lies a symphony of intelligent data structures and algorithms — working tirelessly to anticipate your needs.  
>  
> Welcome to your day, powered by code.

<p align="center">
  <img src="images/story.jpg" alt="A Day in the Googleverse" width="600">
</p>

---

# 🧪 Case Study: How Google Search Delivers the Perfect Result

### 🔍 Scenario: A User Searches for "Best DSLR Cameras"

> On a regular morning, a user types "Best DSLR Cameras for Beginners" into Google. Within milliseconds, Google presents hundreds of relevant, ranked, and refined results. But what’s happening behind the scenes?

# 🛠️ Step 1: String Matching Begins

To match the query to documents, **Rabin-Karp** and **KMP** algorithms are applied for efficient pattern searching across billions of indexed web pages.  
📄 [Details](1.html)

- **Why KMP/Rabin-Karp?**  
  Fast and scalable substring matching by avoiding re-checking characters.

# 🧠 Step 2: Autocomplete Kicks In

Before the user even finishes typing, suggestions like *"Best DSLR Cameras 2025"* pop up — thanks to **Trie** and **Ternary Search Trees** enabling prefix-based lookups in real time.  
📄 [Details](2.html)

- **Why Tries?**  
  Lookup time is reduced to O(L), where L is the length of the prefix.

# 📈 Step 3: Page Ranking Magic

Once results are fetched, they’re sorted using **PageRank**, combined with **DFS** and **BFS** to traverse the web’s graph of interconnected pages.  
📄 [Details](3.html)

- **Why Graph Algorithms?**  
  They evaluate importance based on the number and quality of inbound links.

# 💾 Step 4: Caching for Speed

Frequently visited search results are retrieved from **LRU**, **LFU**, or **HashMap + DLL** caches.  
📄 [Details](4.html)

- **Why Caching?**  
  To serve common queries in constant time.

# 📝 Step 5: Handling Typos

If the user types "Best DSLF Cameraz", Google's spell checker uses **Levenshtein Distance** and **Trigram Matching** to suggest "Best DSLR Cameras".  
📄 [Details](5.html)

- **Why Edit Distance?**  
  Finds the most likely intended query using minimal edits.

# ✅ Final Outcome

- Accurate search results  
- Helpful auto-suggestions  
- Corrected spellings  
- Fast load times due to caching

> 🔎 **Summary**: Google Search isn’t just a black box—it’s a beautifully choreographed system where **graphs**, **tries**, **DP**, and **greedy logic** blend to serve billions daily.

---

# 🧪 Case Study: How Google Maps Gets You There (Fast)

### 🗺️ Scenario: A User Navigates to a Café in Traffic in Hubballi

> A user opens Google Maps and searches for the quickest route to their favorite café. Maps instantly shows directions, live traffic, and nearby recommendations. But what powers this magic?

# 🧭 Step 1: Finding the Shortest Path

Google Maps computes the **fastest route** using **Dijkstra’s**, **A\***, and **Bellman-Ford** algorithms.  
📄 [Details](6.html)

# 🚦 Step 2: Live Traffic Integration

Maps considers **real-time congestion** using **Dynamic Graphs** and **Real-Time A\*** updates.  
📄 [Details](7.html)

# 🗃️ Step 3: Grouping Nearby Places

Maps uses **clustering** (DBSCAN, K-Means, DSU) to group similar POIs.  
📄 [Details](8.html)

# 📍 Step 4: Regional Mapping and Boundaries

Neighborhood outlines, park boundaries, and contours are visualized using **Convex Hull** and **K-D Trees**.  
📄 [Details](9.html)

# ✅ Final Outcome

- Optimal route suggestions  
- Real-time traffic-aware updates  
- Grouped POIs  
- Seamless regional overlays

> 🔎 **Summary**: Google Maps uses graph algorithms, clustering techniques, and spatial structures to deliver real-time navigation.

---

# 🧪 Case Study: How YouTube Organizes the Video World

### 🎬 Scenario: A User Searches for a Trending Video on YouTube

> A user searches for a trending short. YouTube instantly retrieves it and suggests others. What enables this seamless video discovery?

# 📥 Step 1: Indexing the Video Library

YouTube indexes titles, tags, and descriptions using **Suffix Trees** and **Inverted Index**.  
📄 [Details](10.html)

# 🔎 Step 2: Searching for Videos

Search queries are matched using **Suffix Arrays** and **KMP Algorithm**.  
📄 [Details](11.html)

# 📈 Step 3: Detecting Trending Content

YouTube monitors spikes using **Sliding Window** and **Heap-based Counters**.  
📄 [Details](12.html)

# 💾 Step 4: Compressing Videos for Storage

Compression uses **Huffman Coding**, **Arithmetic Coding**, and **RLE**.  
📄 [Details](13.html)

# ✅ Final Outcome

- Exact and relevant video results  
- Trending content in real-time  
- Compressed storage for smooth playback

> 🔎 Summary: YouTube blends pattern matching, trend detection, and compression for a scalable video experience.

---

# 🧪 Case Study: How Google Calendar Keeps You Organized

### 🕒 Scenario: A User Schedules a Meeting Without Conflicts

> A user adds a meeting and sets a recurring schedule. Calendar handles overlaps, timing, and reminders flawlessly.

# 📋 Step 1: Storing and Sorting Events

Sorting uses **Merge Sort**, **Quick Sort**, **Heap Sort**.  
📄 [Details](14.html)

# 🔍 Step 2: Checking Availability

Conflict detection uses **Binary Search**, **Segment Trees**, **Sparse Tables**.  
📄 [Details](15.html)

# ⏰ Step 3: Sending Reminders

Reminders are managed using **Priority Queues**, **Min-Heaps**, **Time Wheels**.  
📄 [Details](16.html)

# 🔁 Step 4: Managing Recurring Events

Repeated events tracked using **Linked Lists**, **Hash Maps**, **Floyd’s Cycle Detection**.  
📄 [Details](17.html)

# ✅ Final Outcome

- Non-overlapping events  
- Timely alerts  
- Seamless recurring schedules

> 🔎 Summary: Google Calendar uses sorting, trees, and priority queues to automate planning.

---

# 🧪 Case Study: How Google Photos Keeps Memories Organized

### 🖼️ Scenario: A User Uploads Vacation Photos

> After uploading, Photos detects duplicates, sorts by timeline, tags faces, and auto-generates albums.

# 🗑️ Step 1: Detecting Duplicate Photos

Duplicates identified using **Hash Tables**, **Bloom Filters**, **Hamming Distance**.  
📄 [Details](18.html)

# 🗂️ Step 2: Creating Albums Automatically

Albums grouped with **K-Means**, **DBSCAN**, **Cosine Similarity**, **Metadata Trees**.  
📄 [Details](19.html)

# 🕒 Step 3: Arranging Timeline View

Timeline sorted using **Radix Sort**, **Bucket Sort**, **Min-Heaps**, **Balanced BSTs**.  
📄 [Details](20.html)

# 👥 Step 4: Grouping Faces Across Photos

Face-tagging modeled as a graph problem using **DSU**, **Euclidean Distance**, **Connected Components**.  
📄 [Details](21.html)

# ✅ Final Outcome

- Duplicate-free albums  
- Auto-grouped memories  
- Timeline and face-wise navigation

> 🔎 Summary: Google Photos blends hashing, clustering, and graphs for smart photo organization.

---

# 📚 References

- [GeeksforGeeks](https://www.geeksforgeeks.org/)  
- Wikipedia (Dijkstra, Trie, Hashing, PageRank, KMP)  
- Stack Overflow Discussions

> 📌 This portfolio outlines the key **Data Structures and Algorithms (DSA)** behind Google’s services, providing insight into real-world applications of theoretical concepts.
