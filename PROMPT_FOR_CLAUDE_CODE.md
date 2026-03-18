# TASK: Build a complete IT Exam Study App (HTML file) with ALL 130 questions

## Reference file
Use `/path/to/full_exam_study_app.html` as the EXACT template for:
- CSS styles (copy verbatim)
- JS rendering logic (copy verbatim) 
- Data structure format per question
- UI behavior (quiz mode, study mode, sidebar, progress, scoring)

The reference file has 44 questions. You must create the same app but with ALL 130 questions listed below.

## CRITICAL RULES
1. Keep EXACTLY the same CSS, JS logic, and HTML structure as the reference file
2. Every question must have: num, original (exact English text from the list), lecture (intro + 3 points with title/text/example), analogy (pl + en), answer (English), keywords
3. Lecture intro and analogy.pl in Polish. Answer in English. Keywords in English.
4. Do NOT skip any question. Verify count = 130 at the end.
5. localStorage for progress tracking (the reference file already has this logic)
6. Output: single .html file

## CLUSTER ASSIGNMENTS (9 clusters + adjust if needed)

### A — AI & Machine Learning
Q1, Q3, Q5, Q6, Q7, Q15, Q27, Q28, Q29, Q30, Q31, Q32, Q33

### B — Bezpieczeństwo IT  
Q4, Q12, Q17, Q34, Q35, Q36, II.6, II.25

### C — Architektura Chmury & Distributed Systems
Q2, Q10, Q11, Q62, Q63, Q64, Q65, Q66, Q67, Q68, Q69, Q70, Q71, Q72, Q73, Q74, Q75, Q76, Q77, Q78, Q79, Q80, Q81, Q82, Q83, Q84, Q85, Q86, Q87, Q88, Q89, Q90, Q91, Q92, Q93, Q94, Q95

### D — OOP & Programowanie
Q41, Q42, Q43, Q44, Q45, Q46, Q47, Q48, Q49, Q50, Q51, Q52, Q53, Q54, Q55, Q56, Q59, Q60, Q96, Q97, Q98, II.1, II.2, II.3, II.4, II.5, II.8, II.10, II.11, II.12, II.13, II.14, II.16, II.17, II.18

### E — Algorytmy & Złożoność
Q20, Q21, Q22, Q23, Q24, Q25, Q26, Q57

### F — Infrastruktura & Systemy Operacyjne
Q8, Q9, Q13, Q14, Q37, Q38, Q39, Q40, II.21

### G — Bazy Danych
Q58, II.22

### H — Web & Mobile Development
Q99, Q100, II.7, II.9, II.15, II.20, II.23, II.24, II.27, II.28, II.30

### I — DevOps & Zarządzanie Projektami
Q16, Q18, Q19, Q61, II.26, II.29

## CHECK: That's 13+8+37+35+8+9+2+11+6 = 129. 
## Missing: Q57 is in E (8 total). II.6 counts. Let me recount...
## Section I: Q1-Q100 = 100 questions
## Section II: II.1-II.30 = 30 questions  
## Total: 130

## QUESTION LIST (exact original English text)

### Section I (Q1-Q100)
Q1. How can AI agents be integrated with the AI methods, such as neural networks and expert systems?
Q2. Explain what hybrid processing is and how it affects the efficiency of distributed systems.
Q3. What data pre-processing techniques can be applied to minimise data errors and data certainty?
Q4. What Zero Trust mechanisms can be applied in order to protect data reliability in IT systems?
Q5. What are the main threats to traditional encryption methods resulting from the development of generative AI?
Q6. What benefits can be brought to business processes by the application of generative AI?
Q7. What models and technologies enable implementation of AI in monitoring business processes?
Q8. How do energy-saving technologies affect the efficiency of computing infrastructure?
Q9. What are the main challenges related to the implementation of energy-saving systems in large computing environments?
Q10. What are the main advantages of hybrid processing in the context of distributed systems?
Q11. How does hybrid processing enable the efficient use of local and cloud resources?
Q12. What challenges related to data security can occur in hybrid environments?
Q13. How does IoT affect the design and functionality of multifunctional robots?
Q14. What types of data collected by IoT sensors are the most useful to multifunctional robots?
Q15. What roles do AI algorithms perform in the development of brain-computer interfaces?
Q16. Present the key differences between traditional methods of project management (e.g.: Waterfall) and agile methods (e.g.: Scrum, Kanban) and discuss situations in which each of these methods can be most efficient, especially in the context of IT projects.
Q17. What are the most frequent threats to the security of ICT networks?
Q18. Discuss the types of tests and benefits brought by test automation in the process of software development.
Q19. What are the most popular version control systems and what are their main advantages and disadvantages while working in large teams?
Q20. How does the analysis of computational (time and memory) complexity affect the choice of an algorithm for a particular task?
Q21. What are the most frequent techniques applied for optimisation of algorithms and in what situations are they most efficient?
Q22. How do time and memory constraints influence the choice between algorithmic optimization and heuristic approaches in solving computational problems?
Q23. How can algorithmic approaches affect the scalability of an IT system?
Q24. What are the consequences of using algorithms with different computational complexities for the scalability of IT systems and their ability to handle a growing number of users?
Q25. What are the key differences between algorithmic and heuristic approaches in solving problems related to IT systems?
Q26. In what situations is a heuristic approach more effective than an algorithmic one, considering the dynamic nature of data and the availability of computational resources?
Q27. How can linear algebra be used in image processing and data analysis in IT systems?
Q28. How can differential and integral calculus contribute to the optimisation of algorithms and predictive models?
Q29. What are the key stages in the process of developing a machine learning model and how do they affect the quality and efficiency of an AI system?
Q30. How do techniques of supervised and unsupervised learning differ in terms of their application and implementation in AI systems?
Q31. What are the best practices in the field of training data management, including its collection, storage, processing and security, in the context of developing AI systems?
Q32. How can large language models (LLMs) be integrated with already existing IT systems and applications to improve their functionality and efficiency?
Q33. How can large language models (LLMs) be used for automation of tasks related to natural language processing, such as translation, text summarizing and sentiment analysis?
Q34. Explain the difference between symmetric and asymmetric encryption.
Q35. DoS (Denial of Service) attacks -- give examples of DoS attacks and how to avoid them.
Q36. What are the most common types of denial-of-service (DoS and DDoS) attacks, what technical, organizational, and legal factors affect system vulnerability to these attacks, and what methods can be used for effective prevention?
Q37. What is virtualization in the context of operating systems and what benefits does it bring?
Q38. What is a hypervisor in virtualization, what role does it perform and how is it organised?
Q39. What is a hypervisor in virtualization, what is its role, and how do infrastructure conditions, such as hardware resources, system architecture, and performance and security requirements, affect its organization and operation?
Q40. Explain what 32 bit and 64 bit operating systems are and why we refer to them.
Q41. How is exception handling implemented in a selected programming language and what are its main mechanisms and best practices?
Q42. How is exception handling implemented in a chosen programming language, what programming constraints influence its efficiency, and what techniques and best practices help minimize the impact of exceptions on code performance and security?
Q43. What are the key differences between a class and an object in object-oriented programming and how do these differences affect the development and use of a code?
Q44. What are the key differences between a class and an object in object-oriented programming across different programming languages, and how does the specificity of a given language affect their definition, creation, and usage in code?
Q45. What is encapsulation in object-oriented programming? What are its main advantages and why is it significant to develop a solid and secure code?
Q46. What is the significance of polymorphism in object-oriented programming and what are the examples of its practical application in various programming languages?
Q47. What are the differences in public, private and protected access modifiers in various programming languages? How do these differences affect the way of managing the access to class members?
Q48. Explain the notions of a class and an object. Defining a class, creating and deleting objects in a selected programming language.
Q49. What is the significance of polymorphism in object-oriented programming, what mechanisms of its implementation exist in different programming languages, and what limitations and possibilities arise from their use?
Q50. Discuss the syntax of defining and differences in passing parameters, returning values and calling object (instance) and class (static) methods in a selected language.
Q51. How are classes defined and objects created and deleted in a chosen programming language, what memory management mechanisms influence the object lifecycle, and what are the performance implications for applications?
Q52. Describe the concept of inheritance and its implementation in a selected object-oriented programming language.
Q53. What are the key differences between automatic and dynamic variables in the context of programming? How do these differences affect memory management and operation of a programme?
Q54. How does the notion of an interface differ from the class implementation in the context of object-oriented programming? What are the main advantages of using interfaces in software development?
Q55. What are the main techniques and advantages of creating new classes by inheritance from already existing classes in object-oriented programming? How does inheritance support code reusing and organisation of class hierarchy?
Q56. What are the differences in syntax for defining instance and class (static) methods in a chosen programming language, how do parameter passing and return values affect their behavior, and what are the consequences of choosing a specific approach for code structure?
Q57. A model developed in Scilab/Matlab is an approximation of the reality. Precise rendering is accompanied by uncertainties, for example, in terms of model parameters, boundary conditions that can affect the accuracy and reliability of results. Discuss these uncertainties on a selected example.
Q58. Discuss and compare relational and non-relational database models.
Q59. What inheritance techniques are available in different programming languages, what are their advantages and limitations, and how do different inheritance models support code reusability and class hierarchy organization?
Q60. Discuss the principles of defining function and class templates (also referred to as generics).
Q61. Name the main features of the unified modelling language (UML) for IT systems -- its application, characteristics and its basic diagrams.
Q62. What are the challenges related to the development and implementation of distributed systems with the use of cloud infrastructure, considering the requirements of scalability, accessibility and coherence of the data?
Q63. What techniques of system design can be applied to integrate distributed applications in the cloud environment, ensuring their high accessibility and fault tolerance?
Q64. What are the advantages and disadvantages of an approach based on microservices in the context of integrating generative AI with systems distributed in a cloud?
Q65. What are the key aspects of software engineering for the development of systems based on distributed processing that use generative AI models in a cloud?
Q66. What methods of IT system modelling can be applied in order to design scalable applications in the cloud architecture?
Q67. How can DevOps and CI/CD processes support the development and implementation of applications based on generative AI in distributed systems operating in a cloud?
Q68. What challenges can be faced by software engineers during the integration of distributed systems with a cloud infrastructure when such systems use generative AI algorithms?
Q69. What design methods may improve fault tolerance in AI systems operating in a distributed environment in a cloud?
Q70. How do system design techniques based on microservices support the use of generative AI in distributed cloud applications?
Q71. What problems related to data coherence can occur during the designing of systems in the distributed architecture? How can such problems be solved with the use of cloud tools?
Q72. How does the cloud architecture support the implementation and integration of distributed processing systems in the context of generative AI?
Q73. What strategies of requirements management are most efficient in the process of developing AI systems, with the consideration of cloud distributed processing services?
Q74. What approach toward software quality management is most appropriate for the development of generative AI systems in the cloud environment?
Q75. What tools and technologies support integration of generative AI with cloud platforms of distributed processing, ensuring the flexibility and scalability of the system?
Q76. What advantages result from using containers (e.g.: Docker) and orchestration (e.g.: Kubernetes) in AI systems based on cloud distributed processing?
Q77. What architectural techniques should be taken into consideration during the design of systems that must operate in real time in cloud distributed systems?
Q78. How does the use of cloud computational infrastructure affect the efficiency of AI algorithms in distributed systems?
Q79. What challenges can be faced in the scaling of systems based on generative AI in cloud distributed environments?
Q80. What techniques of data management are efficient in systems based on distributed processing in a cloud?
Q81. What solutions are available for monitoring and optimising the efficiency of systems operating in a cloud, especially in the context of distributed processing?
Q82. What techniques used in software engineering are significant for the development of distributed systems that use machine learning algorithms in a cloud?
Q83. What challenges related to data security and privacy can occur in systems operating in cloud distributed processing?
Q84. What advantages can be brought by using cloud technologies, such as serverless computing, in the context of generative AI models in distributed applications?
Q85. What mechanisms of synchronisation and communication in distributed systems support the efficient operation of generative AI algorithms in a cloud?
Q86. What design templates are applied most frequently during the development of distributed systems that use generative AI and operate in cloud environments?
Q87. What aspects of distributed system design should be taken into consideration in order to ensure their high efficiency in the context of applications operating in a cloud?
Q88. How does the use of cloud tools for data processing in real time affect the efficiency of AI algorithms?
Q89. What are the advantages of using distributed databases in systems based on distributed processing in a cloud?
Q90. What problems can be faced by system designers in the context of adjusting generative AI algorithms to the specific character of cloud distributed processing?
Q91. What process automation tools can be applied in life-cycle management of systems based on the cloud distributed infrastructure?
Q92. What methods of scaling and optimising cloud resources are most efficient for applications that operate in distributed systems?
Q93. What efficiency-related and technical aspects should be taken into consideration during the design of distributed systems in the context of cloud architecture based on serverless computing?
Q94. What techniques of data storage and data processing are most suitable for generative AI models operating in distributed systems?
Q95. What cloud tools allow for efficient management of AI training processes in cloud distributed systems?
Q96. What is the significance of polymorphism in object-oriented programming and what are the examples of its practical application in various programming languages?
Q97. Discuss the notion of abstraction and indicate its significance in terms of multiple reuse.
Q98. Discuss the conditions of applying an object-oriented and structured approach in IT system design.
Q99. Discuss the principles of MVC template operation. In what projects would you use this type of architecture?
Q100. Name and describe features of various types of mobile applications (native, hybrid, cross-platform, etc.).

### Section II (II.1 - II.30)
II.1. Compare exception handling in Java and .NET, and explain how it affects web application reliability.
II.2. How do Java Servlets and ASP.NET Core middleware handle HTTP requests in web applications?
II.3. Explain how dependency injection works in both Spring Boot (Java) and ASP.NET Core (.NET) for building scalable web applications.
II.4. Discuss the use of asynchronous programming in C# (async/await) and Java (CompletableFuture) for improving web application performance.
II.5. Explain how RESTful APIs are implemented in Java (Spring Boot) and .NET (ASP.NET Web API), and how they can be tested for reliability.
II.6. How does OAuth 2.0 work in securing web and mobile applications, and how can it be implemented in Java and .NET?
II.7. Compare the role of progressive web apps (PWAs) and native mobile apps in cross-platform development using Java and .NET.
II.8. Explain how WebSockets improve real-time communication in web and mobile applications, and how Java and .NET support them.
II.9. Discuss how GraphQL differs from REST and how it can be used to optimize API responses in mobile applications.
II.10. How does Firebase Authentication simplify user authentication for both mobile and web applications?
II.11. How do you perform unit testing in both Java (JUnit) and .NET (xUnit/NUnit) for web and mobile applications?
II.12. Compare the use of mocking frameworks in Java (Mockito) and .NET (Moq) for testing APIs in web and mobile applications.
II.13. Explain how design patterns like Singleton and Factory can be applied in Android (Java/Kotlin) and .NET mobile development (Xamarin/MAUI).
II.14. Discuss how functional programming paradigms (e.g., higher-order functions, immutability) are applied in Java (Streams, Lambdas) and .NET (LINQ, Delegates).
II.15. How can automated UI testing be performed in web and mobile applications using tools like Selenium, Appium, or Cypress?
II.16. How does Spring Boot (Java) and ASP.NET Core implement dependency inversion to achieve modular software design?
II.17. Explain how functional programming concepts (e.g., pure functions, immutability) can be used in embedded systems programming for improved reliability.
II.18. Discuss how multithreading is handled in Java (ExecutorService) and .NET (Task Parallel Library) for performance optimization.
II.19. Explain how microservices architectures improve web application scalability, and how Java (Spring Boot) and .NET (Docker/Kubernetes) support them.
II.20. How do serverless computing platforms like AWS Lambda and Azure Functions enhance web application efficiency?
II.21. Compare memory management techniques in Java (Garbage Collection) and .NET (CLR Memory Management) for mobile and embedded systems.
II.22. How does real-time data processing work in mobile applications using Firebase Realtime Database or SignalR (ASP.NET)?
II.23. What role do event-driven architectures play in embedded systems and mobile applications? Provide examples.
II.24. Explain how Android's WorkManager and iOS Background Tasks help optimize mobile application performance.
II.25. Discuss cybersecurity best practices in Java and .NET to protect web and mobile applications from common attacks like SQL Injection, XSS, CSRF.
II.26. How can CI/CD pipelines be implemented for mobile and embedded systems projects using GitHub Actions, Jenkins, or Azure DevOps?
II.27. Explain how edge computing influences the performance of embedded systems and mobile applications.
II.28. Compare how Bluetooth Low Energy (BLE) and MQTT protocols can be used in IoT-based embedded system projects.
II.29. How do agile methodologies impact team projects in embedded systems programming and software development?
II.30. Discuss the challenges of developing cross-platform applications for embedded systems and mobile devices, and how frameworks like Flutter or MAUI help overcome them.

## UPDATED CLUSTER ASSIGNMENTS (verified 130 total)

### A — AI & Machine Learning (13 questions)
Q1, Q3, Q5, Q6, Q7, Q15, Q27, Q28, Q29, Q30, Q31, Q32, Q33

### B — Bezpieczeństwo IT (8 questions)
Q4, Q12, Q17, Q34, Q35, Q36, II.6, II.25

### C — Architektura Chmury & Distributed Systems (37 questions)
Q2, Q10, Q11, Q62, Q63, Q64, Q65, Q66, Q67, Q68, Q69, Q70, Q71, Q72, Q73, Q74, Q75, Q76, Q77, Q78, Q79, Q80, Q81, Q82, Q83, Q84, Q85, Q86, Q87, Q88, Q89, Q90, Q91, Q92, Q93, Q94, Q95

### D — OOP & Programowanie (35 questions)
Q41, Q42, Q43, Q44, Q45, Q46, Q47, Q48, Q49, Q50, Q51, Q52, Q53, Q54, Q55, Q56, Q59, Q60, Q96, Q97, Q98, II.1, II.2, II.3, II.4, II.5, II.8, II.10, II.11, II.12, II.13, II.14, II.16, II.17, II.18

### E — Algorytmy & Złożoność (8 questions)
Q20, Q21, Q22, Q23, Q24, Q25, Q26, Q57

### F — Infrastruktura & Systemy Operacyjne (9 questions)
Q8, Q9, Q13, Q14, Q37, Q38, Q39, Q40, II.21

### G — Bazy Danych (2 questions)
Q58, II.22

### H — Web & Mobile Development (11 questions)
Q99, Q100, II.7, II.9, II.15, II.19, II.20, II.23, II.24, II.27, II.28, II.30

### I — DevOps & Zarządzanie Projektami (7 questions)
Q16, Q18, Q19, Q61, II.26, II.29

COUNT CHECK: 13+8+37+35+8+9+2+11+7 = 130 ✓

## DATA FORMAT (per question — copy EXACTLY from reference)

```javascript
{num:"Q1",original:"<exact English question text>",
lecture:{intro:"<Polish intro paragraph>",
points:[
{title:"<Polish title>",text:"<Polish explanation>",example:"<Polish concrete example>"},
{title:"<Polish title>",text:"<Polish explanation>",example:"<Polish concrete example>"},
{title:"<Polish title>",text:"<Polish explanation>",example:"<Polish concrete example>"}
]},
analogy:{pl:"<Polish analogy>",en:"<English analogy>"},
answer:"<Full English model answer ready to speak at exam — 4-6 sentences>",
keywords:["keyword1","keyword2","keyword3","keyword4","keyword5","keyword6","keyword7"]}
```

## CONTENT QUALITY REQUIREMENTS
- Lecture intro: 2-3 sentences in Polish, setting context
- Each point: title (Polish), text (3-4 sentences Polish, technical and precise), example (concrete, specific, with real tech names/numbers)
- Analogy: vivid, memorable, one that makes the concept click
- Answer: 4-6 sentences in English, exam-ready, covers all key points, sounds natural when spoken
- Keywords: 5-8 most important English technical terms
- For cloud cluster (C): many questions overlap — give each a UNIQUE angle. Don't just repeat the same content. Q62 focuses on challenges, Q63 on fault tolerance techniques, Q64 on microservices pros/cons, etc.

## BUILD APPROACH
Since this file will be ~400-500KB, build it in parts:
1. Start with the CSS (copy from reference verbatim)
2. Build each cluster's questions one at a time
3. Add the JS logic at the end (copy from reference verbatim)
4. Verify the total question count = 130
5. Output single .html file
