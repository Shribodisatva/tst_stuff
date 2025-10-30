# LLM Benchmark Results

**Generated:** 2025-10-30 15:58:39

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
| deepseek-r1:8b | 2306.00 | 82.22 | 83.50 | 47 | 6969 |
| llama3.1:8b | 1591.93 | 37.67 | 40.71 | 57 | 711 |

---

## Detailed Results

### deepseek-r1:8b

**Average Performance:**

```
Prompt eval: 2306.00 t/s
Response: 82.22 t/s
Total: 83.50 t/s

Stats:
  Prompt tokens: 47
  Response tokens: 6969
  Model load time: 0.07s
  Prompt eval time: 0.02s
  Response time: 89.00s
  Total time: 89.87s
```

**Individual Runs:**

1. ✓ Prompt: `Explain the key differences between Kubernetes Sta...`
   - Response: 86.01 t/s, 2155 tokens, 25.68s
2. ✓ Prompt: `Explain the key differences between Kubernetes Sta...`
   - Response: 83.95 t/s, 2147 tokens, 26.09s
3. ✓ Prompt: `Compare and contrast DevOps and SRE (Site Reliabil...`
   - Response: 84.91 t/s, 2434 tokens, 29.29s
4. ✓ Prompt: `Compare and contrast DevOps and SRE (Site Reliabil...`
   - Response: 85.52 t/s, 2225 tokens, 26.60s
5. ✗ Prompt: `You have 12 identical-looking balls. One ball has ...`
   - Error: 6 validation errors for OllamaResponse
total_duration
  Input should be a valid integer [type=int_type, input_value=None, input_type=NoneType]
    For further information visit https://errors.pydantic.dev/2.10/v/int_type
load_duration
  Input should be a valid integer [type=int_type, input_value=None, input_type=NoneType]
    For further information visit https://errors.pydantic.dev/2.10/v/int_type
prompt_eval_count
  Input should be a valid integer [type=int_type, input_value=None, input_type=NoneType]
    For further information visit https://errors.pydantic.dev/2.10/v/int_type
prompt_eval_duration
  Input should be a valid integer [type=int_type, input_value=None, input_type=NoneType]
    For further information visit https://errors.pydantic.dev/2.10/v/int_type
eval_count
  Input should be a valid integer [type=int_type, input_value=None, input_type=NoneType]
    For further information visit https://errors.pydantic.dev/2.10/v/int_type
eval_duration
  Input should be a valid integer [type=int_type, input_value=None, input_type=NoneType]
    For further information visit https://errors.pydantic.dev/2.10/v/int_type
6. ✓ Prompt: `You have 12 identical-looking balls. One ball has ...`
   - Response: 76.57 t/s, 40960 tokens, 538.38s
7. ✓ Prompt: `Design a URL shortening service (like bit.ly) that...`
   - Response: 79.66 t/s, 3318 tokens, 42.13s
8. ✓ Prompt: `Design a URL shortening service (like bit.ly) that...`
   - Response: 77.42 t/s, 5176 tokens, 67.57s
9. ✓ Prompt: `Explain why some programming languages are signifi...`
   - Response: 80.80 t/s, 2690 tokens, 33.72s
10. ✓ Prompt: `Explain why some programming languages are signifi...`
   - Response: 85.12 t/s, 1615 tokens, 19.41s

### llama3.1:8b

**Average Performance:**

```
Prompt eval: 1591.93 t/s
Response: 37.67 t/s
Total: 40.71 t/s

Stats:
  Prompt tokens: 57
  Response tokens: 711
  Model load time: 0.09s
  Prompt eval time: 0.04s
  Response time: 18.93s
  Total time: 19.49s
```

**Individual Runs:**

1. ✓ Prompt: `Explain the key differences between Kubernetes Sta...`
   - Response: 38.59 t/s, 724 tokens, 19.30s
2. ✓ Prompt: `Explain the key differences between Kubernetes Sta...`
   - Response: 37.48 t/s, 692 tokens, 19.00s
3. ✓ Prompt: `Compare and contrast DevOps and SRE (Site Reliabil...`
   - Response: 37.75 t/s, 707 tokens, 19.27s
4. ✓ Prompt: `Compare and contrast DevOps and SRE (Site Reliabil...`
   - Response: 39.46 t/s, 667 tokens, 17.37s
5. ✓ Prompt: `You have 12 identical-looking balls. One ball has ...`
   - Response: 37.97 t/s, 478 tokens, 13.04s
6. ✓ Prompt: `You have 12 identical-looking balls. One ball has ...`
   - Response: 37.90 t/s, 650 tokens, 17.67s
7. ✓ Prompt: `Design a URL shortening service (like bit.ly) that...`
   - Response: 35.21 t/s, 791 tokens, 23.11s
8. ✓ Prompt: `Design a URL shortening service (like bit.ly) that...`
   - Response: 36.92 t/s, 862 tokens, 23.99s
9. ✓ Prompt: `Explain why some programming languages are signifi...`
   - Response: 38.81 t/s, 740 tokens, 19.70s
10. ✓ Prompt: `Explain why some programming languages are signifi...`
   - Response: 36.57 t/s, 798 tokens, 22.42s

