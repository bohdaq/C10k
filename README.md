# C10k
The name C10k is a numeronym for concurrently handling ten thousand connections. Note that concurrent connections are not the same as requests per second, though they are similar: handling many requests per second requires high throughput (processing them quickly), while a high number of concurrent connections requires efficient scheduling of connections. 

In other words, handling many requests per second is concerned with the speed of handling requests, whereas a system capable of handling a high number of concurrent connections does not necessarily have to be a fast system, only one where each request will deterministically return a response within a (not necessarily fixed) finite amount of time. [Wikipedia](https://en.wikipedia.org/wiki/C10k_problem)


Here is the shell script to test this.
