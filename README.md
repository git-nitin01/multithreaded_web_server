# multithreaded_web_server
- Testing a web server with Single thread, Multithreading and ThreadPooled
- MacOS operating system is used with apache Jmeter to test for 600K requests.
- Since, the request size ~32 bytes that's why you see single thread has higher throughput for a machine like macbook pro, but time range is 0 - 32ms.
- As compared to Multithreaded and Threaded, throughput and deviation is quite stable with requests completing within 1ms.
- Results shows, multithreading takes advantage of high core systems to scale while also pushing boundaries of the Java language.

### Single threaded
<img width="1208" alt="singlethread" src="https://github.com/user-attachments/assets/e1136a2b-b3ac-4214-bde5-83f727bf54f2" />

### Multi threaded
<img width="1208" alt="multithread" src="https://github.com/user-attachments/assets/9045ce96-c5d5-49d8-bbbb-37cc195c5411" />

### Thread Pooling using Executers
<img width="1208" alt="threadpooled" src="https://github.com/user-attachments/assets/643769d6-0e36-497a-bd57-db3973fd6a77" />
