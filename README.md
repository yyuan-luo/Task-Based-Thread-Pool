# Task-Based-Thread-Pool
A thread pool that uses a task-based approach combined with work stealing. Each thread in the pool will have its own local task queue. When a thread completes its tasks, it can "steal" tasks from the queues of other threads, improving load balancing
