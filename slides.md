---
marp: true
theme: custom
paginate: true
header: "Product Documentation"
footer: "24f2005754@ds.study.iitm.ac.in"
style: |
  section {
    font-family: 'Segoe UI', sans-serif;
    color: #333;
  }
  h1 {
    color: #2a9d8f;
  }
  h2 {
    color: #e76f51;
  }
---

# Product Documentation
**Technical Writing Team**  
Email: 24f2005754@ds.study.iitm.ac.in

---

<!-- Slide with Background Image -->
---
# Product Overview
_backgroundImage: url('https://via.placeholder.com/800x600.png?text=Product+Background')

- Maintainable in version control  
- Easy to convert to PDF, HTML, and PPTX  
- Supports diagrams, math, and code  

---

# Features
- Feature A: Fast and reliable
- Feature B: User-friendly UI
- Feature C: Extensible architecture

---

# Algorithmic Complexity
- Sorting Algorithm Complexity:

$$T(n) = O(n \log n)$$

- Space Complexity:

$$S(n) = O(n)$$

---

# Code Example
```python
def quicksort(arr):
    if len(arr) <= 1:
        return arr
    pivot = arr[len(arr) // 2]
    left = [x for x in arr if x < pivot]
    middle = [x for x in arr if x == pivot]
    right = [x for x in arr if x > pivot]
    return quicksort(left) + middle + quicksort(right)
