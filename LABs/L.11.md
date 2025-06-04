
# W11 - Zero-Sum Games - Tik Tak Toe 

**Lab Session Tasks:**

Students are required to implement and test their project code with the following objectives:

* **Apply the Alpha-Beta pruning algorithm** in the game logic to optimize decision-making.
* **Increase the board size** for the game to support **100x100** and **1000x1000** dimensions.
* **Measure the time** taken to select each move using the Alpha-Beta algorithm, and analyze performance under different board sizes.

## Python code

```Python

import time

start_time = time.perf_counter()  # lấy thời gian bắt đầu (chính xác đến microsecond)

# ... đoạn code cần đo thời gian ...

end_time = time.perf_counter()  # lấy thời gian kết thúc

elapsed_time = end_time - start_time  # tính thời gian đã trôi qua

print(f"Elapsed time: {elapsed_time:.6f} seconds")


```
