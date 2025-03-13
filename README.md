# Week 5

## Pre-profling and optimization

### all-student-name

| Listener Name | Result Image | 
| ------------- | -----------  |
| View Results Tree | ![Image](https://github.com/user-attachments/assets/517fea55-7c5d-450c-9e98-4835edbd9691) |
| View Results in Table | ![Image](https://github.com/user-attachments/assets/f034c557-cb63-4f94-94fc-4f31c39f9889) |
| Summary Report | ![Image](https://github.com/user-attachments/assets/f381fcf0-6231-4afc-9f1b-d3a216d406fb) |
| Graph Result |  ![Image](https://github.com/user-attachments/assets/708b7540-4185-40b3-b2e6-1938ef54f5bc) |

#### highest-gpa

| Listener Name | Result Image | 
| ------------- | -----------  |
| View Results Tree | ![Image](https://github.com/user-attachments/assets/e724e252-ea81-479b-bc05-07a34e51b9b3) | 
| View Results in Table | ![Image](https://github.com/user-attachments/assets/078c5411-f156-4aab-ad63-9365270ef9a3) | 
| Summary Report | ![Image](https://github.com/user-attachments/assets/7bcd08ff-df3c-4d5b-a390-65589c07b363) |
| Graph Result | ![Image](https://github.com/user-attachments/assets/84723252-0b98-4b25-bf1e-5fa283725e41) |

### Command Line

### all-student-name

| Command Line | Log File Results |
| ------------ | ---------------- |
| ![Image](https://github.com/user-attachments/assets/bc1a6016-7fb3-49ed-b6f0-ad3d51059751) | ![Image](https://github.com/user-attachments/assets/a8c1e898-90d8-4fa2-bba3-5b475e2def07) |

### highest-gpa

| Command Line | Log File Results |
| ------------ | ---------------- |
| ![Image](https://github.com/user-attachments/assets/7c8fb59f-686e-40f5-b118-989ebcf556b2) | ![Image](https://github.com/user-attachments/assets/94fc969c-e562-49c4-a29d-7d7a5acb58d6) | 

## Post-profiling and optimization

### all-student-name

| Listener Name | Result Image | 
| ------------- | -----------  |
| View Results Tree | ![Image](https://github.com/user-attachments/assets/dcea04a2-2a21-43bf-8a2d-53f2e6198c2e) |
| View Results in Table | ![Image](https://github.com/user-attachments/assets/0197746b-53df-49f9-b2eb-9c8bd681f6e3) |
| Summary Report | ![Image](https://github.com/user-attachments/assets/80e7e854-3c79-4bf8-99b8-1b78e330810e) |
| Graph Result |  ![Image](https://github.com/user-attachments/assets/577dce13-68d1-4c0a-8754-504c784c42bb) |

#### highest-gpa

| Listener Name | Result Image | 
| ------------- | -----------  |
| View Results Tree | ![Image](https://github.com/user-attachments/assets/f59b53bf-55e5-4024-bbe3-eb8f3cbe1093) | 
| View Results in Table | ![Image](https://github.com/user-attachments/assets/da3ebd76-4d3c-459f-baf4-40fa44726f19) | 
| Summary Report | ![Image](https://github.com/user-attachments/assets/de0b12b4-6a33-4886-b991-e3c4105d40e7) |
| Graph Result | ![Image](https://github.com/user-attachments/assets/ec746213-95d3-456f-878b-08c6449249ac) |

### Command Line

### all-student-name

| Log File Results |
| ---------------- |
| ![Image](https://github.com/user-attachments/assets/4cc9a7ed-a1e3-4996-a89f-8d02d1874d27) |

### highest-gpa

| Log File Results |
| ---------------- |
| ![Image](https://github.com/user-attachments/assets/6d7c17d9-8da2-4ed6-b110-f80d74332011) |

## Conclusion

By implementing optimizations such as query refinements, repository improvements, and more efficient data handling, 
I achieved a significant performance boost. Profiling played a key role in identifying bottlenecks and guiding targeted improvements, 
leading to significantly faster response times across endpoints.
   
This demonstrates the crucial role of performance analysis and optimization in ensuring a system runs smoothly. 
Identifying inefficiencies and refining data retrieval methods led to faster execution and better resource utilization. 
Regular monitoring and targeted enhancements are key to maintaining a high-performing and scalable application.

### Reflection

1. **What is the difference between the approach of performance testing with JMeter and profiling with IntelliJ Profiler in the context of optimizing application performance?**
   
   JMeter focuses on external performance, simulating user requests to identify slow endpoints, database latency, and system bottlenecks under load. In contrast, 
   IntelliJ Profiler analyzes internal performance, tracking CPU usage, memory allocation, and method execution to pinpoint inefficient code and resource-heavy operations. 
   JMeter helps assess scalability and response times, while IntelliJ Profiler is used for fine-tuning code efficiency.

2. **How does the profiling process help you in identifying and understanding the weak points in your application?**
   
   Profiling helps identify weak points in an application by analyzing CPU usage, memory consumption, execution time, and thread behavior. 
   It detects slow methods, memory leaks, inefficient computations, and redundant operations, allowing developers to optimize performance. 
   Profiling also reveals database inefficiencies and excessive resource usage, helping streamline execution.

3. **Do you think IntelliJ Profiler is effective in assisting you to analyze and identify bottlenecks in your application code?**
   
   Yes, IntelliJ Profiler is highly effective in identifying bottlenecks in application code by providing insights into CPU usage, 
   memory allocation, and execution time. It helps pinpoint slow methods, inefficient loops, and resource-heavy operations, 
   making it a valuable tool for performance optimization.

4. **What are the main challenges you face when conducting performance testing and profiling, and how do you overcome these challenges?**

   When conducting performance testing, I face some challenges like selecting the right metrics, handling inconsistent results, and interpreting profiling data. To overcome these, I focus on key performance metrics based on the system’s needs, 
   run multiple tests in a controlled environment to reduce inconsistencies, and use visual profiling tools to make data interpretation easier.

6. **What are the main benefits you gain from using IntelliJ Profiler for profiling your application code?**

   IntelliJ Profiler helps find slow code, reduce memory use, and make programs run faster. It shows how functions are called and tracks performance in real time, making it easier to improve code without making unnecessary changes.

6. **How do you handle situations where the results from profiling with IntelliJ Profiler are not entirely consistent with findings from performance testing using JMeter?**
   
   If profiling results differ from JMeter performance tests, I analyze both perspectives—JMeter reflects on external execution, while IntelliJ Profiler focuses on internal execution. 
   Cross-referencing both helps in identifying whether the issue is code-related or system-related.

7. **What strategies do you implement in optimizing application code after analyzing results from performance testing and profiling? How do you ensure the changes you make do not affect the application's functionality?**
   
   After analyzing profiling and testing results, I implement optimizations such as algorithm improvements. To ensure functionality remains intact, I perform  some necessary tests (e.g. unit tests), then compare pre- and post-optimization benchmarks before deployment.
