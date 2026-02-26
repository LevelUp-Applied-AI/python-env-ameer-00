==================================================
SYSTEM INFORMATION
==================================================
OS:         Windows 11
Version:    10.0.26200
Machine:    AMD64
Processor:  Intel64 Family 6 Model 154 Stepping 3, GenuineIntel
Python:     3.12.8 (tags/v3.12.8:2dc476b, Dec  3 2024, 19:30:04) [MSC v.1942 64 bit (AMD64)]

Benchmark 1 — sum(range(5,000,000))
  Result:  12,499,997,500,000
  Time:    0.0499 seconds

Benchmark 2 — list comprehension (n=1,000,000)
  First 5: [0, 1, 4, 9, 16]
  Time:    0.0411 seconds

Benchmark 3 — string join (n=100,000)
  Length:  588,889 characters
  Time:    0.0088 seconds

==================================================
SUMMARY
==================================================
  sum benchmark:    0.0499s
  list benchmark:   0.0411s
  string benchmark: 0.0088s

