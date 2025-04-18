# sort-data-with-less-memory


This algorithm is used to **sort very large files** that do **not fit into your computer’s RAM**. Instead of loading the entire file into memory, it splits the file into smaller parts, sorts them one by one, and then merges them into a single sorted file.

---

## How It Works 

### Step 1: Split the Data
Break the big file into smaller chunks that **can fit into RAM**.  
For example, if your RAM can hold 1 GB, make 1 GB or less memory chunks.

### Step 2: Sort Each Chunk
Sort each chunk one by one in memory using in place sorting algorithm and save them as **temporary sorted files**.

### Step 3: Start Merging
Open all sorted chunks and **take the first number** from each one.

### Step 4: Find the Smallest
From the current numbers, **pick the smallest** and write it to the final sorted file.

### Step 5: Repeat
Get the next number from the same chunk where the smallest came from, and **repeat** until all numbers are sorted.





