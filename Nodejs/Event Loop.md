- single-threaded loop responsible for handling all asynchronous tasks.
- connecting the queue (micro and macro queue) to the call stack.
- a runtime construct instead of as a library.
- Node.js simply enters the event loop after executing the input script.
- Node.js exits the event loop when there are no more callbacks to perform.
- in other  systems, their is always a blocking call to start the event-loop.
- event loop is hidden from the user in browser.

> [!INFO] Event loop in Node.js as a runtime construct instead of as a library.

> [!INFO] in other system their is a blocking call to start the event-loop.