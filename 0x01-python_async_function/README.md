## Project Description
Learn `async` and `await` syntax.
How to execute an async program with `asyncio`.
How to run concurrent coroutines.
How to create `asyncio` tasks.
How to use the `random` module.


* **0. Basic annotations - add** - Write a type-annotated function `add` that takes a float `a` and a float `b` as arguments and returns their sum as a float. - `0-basic_async_syntax.py`.
* **1. Let's execute multiple coroutines at the same time with async** - Import `wait_random` from the previous file and write an async routine called `wait_n` that takes in 2 int arguments (in this order): `n` and `max_delay`. You will spawn `wait_random` n times with the specified max_delay. - `1-concurrent_coroutines.py`.
* **2. Measure the runtime** - Import `wait_n ` from the previous file and create a `measure_time` function with integers `n` and `max_delay` as arguments that measures the total execution time for `wait_n(n, max_delay)`, and returns `total_time / n`. - `2-measure_runtime.py`.
* **3. Tasks** - Import `wait_random` from `0-basic_async_syntax`. Write a function `task_wait_random` that takes an integer `max_delay` and returns a `asyncio.Task`. - `3-tasks.py`.
* **4. Tasks** - Take the code from `wait_n` and alter it into a new function `task_wait_n`. The code is nearly identical to `wait_n` except `task_wait_random` is being called. - `4-tasks.py`.

