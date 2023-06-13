# Golang-Producer-Consumer-Problem
In computing, the producer-consumer problem (also known as the bounded-buffer problem) is a family of problems described by Edsger W. Dijkstra since 1965. This is an example of a solution to it using Golang.

## Problem statement 
In operating System Producer is a process which is able to produce data/item.
Consumer is a Process that is able to consume the data/item produced by the Producer.
Both Producer and Consumer share a common memory buffer. This buffer is a space of a certain size in the memory of the system which is used for storage. The producer produces the data into the buffer and the consumer consumes the data from the buffer.

- Producer Process should not produce any data when the shared buffer is full.
- Consumer Process should not consume any data when the shared buffer is empty.
- The access to the shared buffer should be mutually exclusive i.e at a time only one process should be able to access the shared buffer and make changes to it.

For consistent data synchronization between Producer and Consumer, the above problem should be resolved.
