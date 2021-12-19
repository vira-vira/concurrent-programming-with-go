# concurrent-programming-with-go

What I will learn:
- How to use go routines
- How to use waitgroups and mutexes
- How to use channels


### Concurrency and Parallelism
- Single Taslk
- Concurrency (multiple task)
- Parallelism (execute multiple task simultaneously)

### Threads vs Goroutines

| Thread| Goroutines|
|-------|:----------|
| Have own execution stack| Have own execution stack|
| Fixed stack space(around 1 MB)| Variable stack space (starts @2 KB)|
| Managed by OS| Managed by Go runtime|

### Working with Goroutines
- Enable concurrent programming
### The Sync Package
- Allow goroutines to coordinate their work

### Channels
- Provide a safe way for goroutines to communicate