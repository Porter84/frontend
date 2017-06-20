# Testing

## Useful Articles
 - [Acceptance Testing](http://softwaretestingfundamentals.com/acceptance-testing/)
 - [System testing](http://softwaretestingfundamentals.com/system-testing/)
 - [Integration Testing](http://softwaretestingfundamentals.com/integration-testing/)
 - [Unit Testing](http://softwaretestingfundamentals.com/unit-testing/)
 - [TDD vs BDD](https://codeutopia.net/blog/2015/03/01/unit-testing-tdd-and-bdd/)
 - [BDD](https://en.wikipedia.org/wiki/Behavior-driven_development)
 - [TDD](https://en.wikipedia.org/wiki/Test-driven_development)
 - [TDD](https://www.typemock.com/test-driven-development-tdd/)
 - [Benefits of test driven development](https://www.madetech.com/blog/9-benefits-of-test-driven-development)
 - [Advantages of TDD](https://agilepainrelief.com/notesfromatooluser/2008/10/advantages-of-tdd.html#.WUkSwmjyiUk)
 - [Benefits of BDD](https://dzone.com/articles/a-few-benefits-you-get-by-doing-bdd)

## Common Questions
**1. What are the differences between TDD and BDD aproaches? What JS frameworks for TDD/BDD you know?**  
- TDD or Test-Driven Development is a process for when you write and run your tests before implemnent the feature.
- BDD or Behavior-Driven Development is a software development process which combines the general techniques and principles of TDD. BDD is an idea about how software development should be managed by both business side and technical side. Technically BDD is an extension of TDD with a domain-specific scripting language. These domain specific languages convert structured natural language statements into executable tests. The result is a closer relationship to acceptance criteria for a given function and the tests used to validate that functionality.
- Obvious the biggest difference is thta in BDDyou write test cases in a natural language that non-programmers are able to read.
- TDD JS frameworks: Jasmin
- BDD JS frameworks: Mocha, CucmberJS

**2. What are benefits of TDD?**  
- safer refactoring
- fewer bugs/less debugging
- increased test coverage
- simplification - write the minimal code that will pass the tests

**3. What are the disadvantages of TDD**  
- hard to learn
- it can reduce the productivity for 2-4 months after starting

**4. What are the benefits of BDD?**  
- strong collaboration: all members of the project have a strong understanding
- the software design follows business value
- the domain specific language is understandable by all members
- more confidence from the developers side

**5. What tools are you using to test ability of your site to look equally in necessary browsers?**  

**6. What's the difference between unit, functional, acceptance, and integration tests? Which problems these solves? Best practices? Drawback? Coverage?**  

**7. What is integrational and e2e tesing? Which problems these solves? Best practices? Drawback? Coverage?**  

**8. How do you test your code?**  

**9. How will you convince your team member to start using TDD?**  

**10. What is your Unit Tests covering process? What is acceptable Code Coverage level?**  

**11. How can I use testing when rewriting code legacy code to a new code base?**  

**12. What is unit testing? What is a unit?**  
- unit testing is a software testing method by which individual units of source code
- unit tests are short code fragments created by programmers or occasionally by white box testers during the development process. It forms the basis for component testing.
- a unit is the smallest testable part of an application.
- In procedural programming, a unit could be an entire module, but it is more commonly an individual function or procedure.
- In object-oriented programming, a unit is often an entire interface, such as a class, but could be an individual method.

**13. What is integration testing?**  
- Integration testing is the phase in software testing in which individual software modules are combined and tested as a group. It occurs after unit testing and before validation testing.
- Integration testing takes as its input modules that have been unit tested, groups them in larger aggregates, applies tests defined in an integration test plan to those aggregates, and delivers as its output the integrated system ready for system testing.

**14. What is smoke testing?**  
- Smoke testing is preliminary testing to reveal simple failures severe enough to reject a prospective software release. A smoke tester will select and run a subset of test cases that cover the most important functionality of a component or system, to ascertain if crucial functions of the software work correctly. 

**15. What is end-to-end testing?**  
- End-to-end testing is a technique used to test whether the flow of an application right from start to finish is behaving as expected. The purpose of performing end-to-end testing is to identify system dependencies and to ensure that the data integrity is maintained between various system components and systems.

**16. What is penetration testing?**  
- A penetration test, is an attack on a computer system that looks for security weaknesses, potentially gaining access to the computer's features and data.

**17. What is load testing?**  
- Load testing is the process of putting demand on a software system or computing device and measuring its response.
- Load testing is performed to determine a system's behavior under both normal and anticipated peak load conditions. It helps to identify the maximum operating capacity of an application as well as any bottlenecks and determine which element is causing degradation.
- When the load placed on the system is raised beyond normal usage patterns to test the system's response at unusually high or peak loads, it is known as stress testing. The load is usually so great that error conditions are the expected result, but there is no clear boundary when an activity ceases to be a load test and becomes a stress test.

**18. What is A/B testing?**  
- In marketing and business intelligence, A/B testing is a term for a randomized experiment with two variants, A and B. In online settings, such as web design (especially user experience design), the goal of A/B testing is to identify changes to web pages that increase or maximize an outcome of interest (e.g., click-through rate for a banner advertisement). A/B testing is a way to compare two versions of a single variable typically by testing a subject's response to variable A against variable B, and determining which of the two variables is more effective.

**19. What is regression testing?**  
- Regression testing is a type of software testing that verifies that software previously developed and tested still performs correctly after it was changed or interfaced with other software. Changes may include software enhancements, patches, configuration changes, etc. During regression testing, new software bugs or regressions may be uncovered. The purpose of regression testing is to ensure that changes such as those mentioned above have not introduced new faults. One of the main reasons for regression testing is to determine whether a change in one part of the software affects other parts of the software. Common methods of regression testing include rerunning previously completed tests and checking whether program behavior has changed and whether previously fixed faults have re-emerged. Regression testing can be performed to test a system efficiently by systematically selecting the appropriate minimum set of tests needed to adequately cover a particular change.

**20. What is the difference between functional and non-functional testing?**  
- Functional testing is performed using the functional specifications provided by the client or you can say by using the design specifications like use cases provided by the design team.
- Non Functional Testing is that which is always concerned with the client expectations like performance, load and stress issues and so on. For example: performance testing, load testing.

**21. What is the difference between black-box and white-box testing approaches?**  
- Black-box testing (also known as functional testing) treats software under test as a black-box without knowing its internals. Tests are using software interfaces and trying to ensure that they work as expected.
- White-box testing (also known as clear box testing, glass box testing, transparent box testing, and structural testing) looks inside the software that is being tested and uses that knowledge as part of the testing process. If, for example, exception is thrown under certain conditions, test might want to reproduce those conditions. White-box testing requires internal knowledge of the system and programming skills.

**22. What tools you can use for the testing methods above?**  
- unit: Junit, EasyMock, Karma, Jasmin, Mocha, Swagger, SOAP UI,
- integration: JUnit, Mockito,
- smoke
- end-to-end: Protractor, Selenium
- load: Apache JMeter
- A/B: Google Analytics Experiments
- regression: Selenium
