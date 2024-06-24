Self-Assessment: Onion Architecture, MVC, and Web API (.NET Core) with Bottlenecks (Encountered)
Conceptual Understanding:
 
Onion Architecture: (Yes/No) 
Have you heard of the Onion Architecture principle in software design?
Answer:
No
 
MVC Pattern: (Yes/No) 
Are you familiar with the Model-View-Controller (MVC) pattern for building web applications?
Answer: 
Yes 
 
Web API: (Yes/No) 
Do you understand the concept of building RESTful APIs using ASP.NET Core Web API?
Answer: 
Yes
 

Application & Bottlenecks:
Onion Architecture:
 
 
Benefits: (1-3 keywords)
Briefly list some key benefits of using Onion Architecture in .NET Core projects. (e.g., separation of concerns, testability)
Answer:
Separation of concerns
Testability
Maintainability
 
 
 
Bottlenecks (Encountered): (Yes/No and Briefly Explain)
Have you encountered any challenges with Onion Architecture in your projects? If so, briefly describe the bottleneck(s). (e.g., Increased complexity for simple projects, difficulty finding developers familiar with the pattern)
Answer: 
Yes, because this is the first time we interact with the Onion Architecture, which makes it really difficult for me.
One possible bottleneck with Onion Architecture is increasing complexity, especially with smaller or simpler projects. Onion Architecture's layers and abstractions may be overkill for projects with simple needs, resulting in excessive development effort and upkeep.
And as someone who is unfamiliar with the pattern, it is really difficult for me. I've had minimal familiarity with building patterns in general.
 
 

MVC:

Components: (1-3 keywords each)
Briefly describe the roles of the Model, View, and Controller in the MVC pattern.
Answer:
Model: Data management, business logic
View: Presentation, user interface
Controller: Handling user input, interaction logic
 
 
 
Bottlenecks (Encountered): (Yes/No and Briefly Explain)
Have you encountered any challenges with tight coupling between Model and Controller in MVC projects? If so, briefly describe the issue(s). (e.g., Difficulty in unit testing controllers, logic changes rippling through the application)
Answer:
Yes, Controller is problematic since it is in separation. Controller relies significantly on the model for data and logic, therefore it became tough to test controller.
 
 

Web API:
Differences from MVC: (Yes/No and Briefly Explain)
Can you differentiate between traditional MVC applications and Web APIs? Briefly explain the main difference.
Answer:
Yes, Traditional MVC applications are meant to offer HTML content to web browsers, with a focus on the display layer (View) as well as user interaction (Controller) and data management (Model). Web APIs, on the other hand, are designed mostly to deliver data and services to client applications over HTTP, often offering data in JSON or XML format rather than HTML. Web APIs often do not include a View component and instead focus on exchange of data and service providing.


 
Bottlenecks (Encountered): (Yes/No and Briefly Explain)
Have you encountered any performance challenges with traditional MVC applications compared to Web APIs? If so, briefly describe the scenario(s). (e.g., Frequent page refreshes causing performance overhead, complex data exchange requiring a more lightweight approach)
Answer:
No, However, in cases where page refreshes are frequent, typical MVC apps may face performance cost owing to the requirement to produce and render HTML pages dynamically. Web APIs, on the other hand, often manage data sharing in a more lightweight manner, which can be useful in circumstances involving complicated data exchange or for improving client-server communication performance.
