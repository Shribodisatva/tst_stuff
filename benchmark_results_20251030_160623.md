# LLM Benchmark Results

**Generated:** 2025-10-30 16:35:13

## System Information

- **Hostname:** Main
- **OS:** Linux 4.4.0-19041-Microsoft
- **Python:** 3.8.10
- **Ollama:** Unknown
- **CPU:** AMD Ryzen 9 5900X 12-Core Processor (24 cores)
- **RAM:** 31.9 GB
- **GPU:** Not available (CPU only)

---

## Summary

| Model | Prompt Eval (t/s) | Response (t/s) | Total (t/s) | Avg Prompt Tokens | Avg Response Tokens |
|-------|-------------------|----------------|-------------|-------------------|---------------------|
| deepseek-r1:8b | 2115.56 | 80.98 | 81.96 | 49 | 12720 |
| llama3.1:8b | 3132.93 | 86.86 | 93.67 | 57 | 736 |

---

## Detailed Results

### deepseek-r1:8b

**Average Performance:**

```
Prompt eval: 2115.56 t/s
Response: 80.98 t/s
Total: 81.96 t/s

Stats:
  Prompt tokens: 49
  Response tokens: 12720
  Model load time: 0.07s
  Prompt eval time: 0.03s
  Response time: 161.96s
  Total time: 163.26s
```

**Individual Runs:**

1. ✓ Prompt: `Explain the key differences between Kubernetes Sta...`
   - Response: 84.24 t/s, 2267 tokens, 27.47s
2. ✓ Prompt: `Explain the key differences between Kubernetes Sta...`
   - Response: 84.96 t/s, 2410 tokens, 28.93s
3. ✓ Prompt: `Compare and contrast DevOps and SRE (Site Reliabil...`
   - Response: 80.34 t/s, 2144 tokens, 27.05s
4. ✓ Prompt: `Compare and contrast DevOps and SRE (Site Reliabil...`
   - Response: 85.75 t/s, 2056 tokens, 24.51s
5. ✓ Prompt: `You have 12 identical-looking balls. One ball has ...`
   - Response: 78.71 t/s, 40960 tokens, 523.93s
6. ✓ Prompt: `You have 12 identical-looking balls. One ball has ...`
   - Response: 77.68 t/s, 10645 tokens, 138.16s
7. ✓ Prompt: `Design a URL shortening service (like bit.ly) that...`
   - Response: 78.77 t/s, 21259 tokens, 271.87s
8. ✓ Prompt: `Design a URL shortening service (like bit.ly) that...`
   - Response: 77.16 t/s, 40960 tokens, 534.28s
9. ✓ Prompt: `Explain why some programming languages are signifi...`
   - Response: 80.94 t/s, 2272 tokens, 28.52s
10. ✓ Prompt: `Explain why some programming languages are signifi...`
   - Response: 81.29 t/s, 2230 tokens, 27.87s

### llama3.1:8b

**Average Performance:**

```
Prompt eval: 3132.93 t/s
Response: 86.86 t/s
Total: 93.67 t/s

Stats:
  Prompt tokens: 57
  Response tokens: 736
  Model load time: 0.09s
  Prompt eval time: 0.02s
  Response time: 8.49s
  Total time: 8.96s
```

**Individual Runs:**

1. ✓ Prompt: `Explain the key differences between Kubernetes Sta...`
   - Response: 87.16 t/s, 708 tokens, 8.58s
2. ✓ Prompt: `Explain the key differences between Kubernetes Sta...`
   - Response: 87.12 t/s, 710 tokens, 8.60s
3. ✓ Prompt: `Compare and contrast DevOps and SRE (Site Reliabil...`
   - Response: 86.67 t/s, 648 tokens, 7.91s
4. ✓ Prompt: `Compare and contrast DevOps and SRE (Site Reliabil...`
   - Response: 86.94 t/s, 650 tokens, 7.91s
5. ✓ Prompt: `You have 12 identical-looking balls. One ball has ...`
   - Response: 86.36 t/s, 541 tokens, 6.65s
6. ✓ Prompt: `You have 12 identical-looking balls. One ball has ...`
   - Response: 89.31 t/s, 600 tokens, 7.12s
7. ✓ Prompt: `Design a URL shortening service (like bit.ly) that...`
   - Response: 85.59 t/s, 1177 tokens, 14.44s
8. ✓ Prompt: `Design a URL shortening service (like bit.ly) that...`
   - Response: 86.21 t/s, 766 tokens, 9.36s
9. ✓ Prompt: `Explain why some programming languages are signifi...`
   - Response: 86.60 t/s, 794 tokens, 9.67s
10. ✓ Prompt: `Explain why some programming languages are signifi...`
   - Response: 86.68 t/s, 771 tokens, 9.39s

