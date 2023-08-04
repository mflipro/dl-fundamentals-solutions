This is based on a n1-standard-4 (4 vCPU, 15GB memory) GCP VM with a single Nvidia V100 GPU.

| precision option | elapsed time for 3 epochs | test accuracy     |
| ---------------- | ------------------------- | ----------------- |
| 64-true          | 54.24 min                 | 0.9265000224113464|
| 32-true          | 26.86 min                 | 0.9225000143051147|
| 16-true          | not supported             | not supported     |
| 16-mixed         | 11.29 min                 | 0.9264000058174133|
| bf16-mixed       | not supported             | not supported     |