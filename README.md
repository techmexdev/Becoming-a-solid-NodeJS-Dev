# Becoming-a-solid-NodeJS-Dev
Notes taken from Igor Soarez's Nodeconf Barcelona talk ["Becoming a solid Node.js developer"](https://www.youtube.com/watch?v=eRXLh526Hyk)

## Capable developer
- Able to build modular Node.js applications
- Able to troubleshoot and debug
- Doesn't create callback (or promise) hell scenarios
- Writes tests
- Makes use of streaming

### What to focus on?
- What is Node? What is Node good for?
- File modules, npm modules
- Organizing and managing dependencies
- Callbacks, Timers, Event Emitter
- Using streams
- Proper error handling
- Debugging
- Module testing
- Using async
- Using HTTP
- Hapi or Express
---

## Efficient developer
- Advanced flow control, is able to throttle concurrent events
- Strong understanding of the event loop
- Faster at debugging and troubleshooting
- Is quickly able to contribute when joining an on-going project
- Knows how to scale node applications
- Knows what not to use -- Cluster, TLS termination, etc

### What to focus on?
- Understanding the event loop
- Using work queues
- Implementing custom streams
- Properly dealing with configuration
- Efficient interaction with databases
- I/O throttling
- RPC
- Integration testing
---

## Pro developer
- Understands how Node works
- Knows some of the internals. How node connects to libuv and v8
- Understanding of libuv
- Basic unserstanding of v8
- Able to troubleshoot performance issues
- Able to succesfully implement custom TCP protocols

### What to focus on?
- Network prorocols
- Theory of distributed systems
- Fault tolerance
- Operating Systems
- Native modules
- Performance debugging tools
- libuv
- v8
