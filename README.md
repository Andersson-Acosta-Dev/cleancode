# cleancode

## [What is clean code](https://www.sonarsource.com/solutions/clean-code/#:~:text=Clean%20Code%20is%20code%20that's,value%20out%20of%20your%20software.)
First of all clean code is code that's easy to read, maintain, understand and change through structure and consistency yet remains robust and secure to withstand performance demands. It lets us get the most value out of our software.

## Principals and best practices of clean code
In order to deliver software that is of high quality, reliable, maintainable, and secure, it is imperative that the underlying code is robust. As a mean to achieve the agility, velocity, and scale of development needed for their business goals. 

### Consistent 
The code is written in a uniform and conventional way. All the code looks similar and follows a regular pattern, even with multiple contributors at different times. Consistent code is **formatted**, **conventional**, and **identifiable**. For example, when code is formatted well, it is systematic and regular, which reduces differences between authors’ coding styles and makes code much easier to review by peers on pull requests.

-**Formatted**: The code presentation is well-organized, systematic, and regular.

-**Conventional**: The code performs tasks with expected instructions.

-**Identifiable**: The names follow a regular structure based on language conventions without arbitrary differences.

### Intentional code
The code is clear, precise, and purposeful. Intentional code reads like it is written with attention and care to convey its purpose. Every instruction makes sense, is adequately formed, and simply communicates its behavior. Intentional code is clear, logical, complete, and efficient. For example, clear code is self-explanatory and transparently communicates its functionality, making it easier to understand the program and reducing the likelihood of bugs being introduced.

-**Clear**: The code is self-explanatory, transparently communicating its functionality.

-**Logical**: The code has well-formed and sound instructions that work together.

-**Complete**: The code constructs are comprehensive and used adequately and thoroughly.

### Adaptable code
The code is structured to evolve easily and with confidence. It makes extending or repurposing its parts easy and promotes localized changes without undesirable side effects. Adaptable code is focused, distinct, modular, and tested. For example, when code is modular it is organized and distributed to emphasize the separation between its parts, making it easier to manage and clearly define the relationships within.

-**Focused**: The code has a single, narrow, and specific scope.

-**Distinct**: The code procedures and data are unique and distinctive, without undue duplication.

-**Modular**: The code has been organized and distributed to emphasize the separation between its parts.

-**Tested**: The code has automated quality tests that provide confidence in the functionality.

### Responsible code
The code takes into account its ethical obligations on data and the potential impact of societal norms. Responsible code is lawful, trustworthy, and respectful. For example, when we classify code as lawful, we refer to it as code that respects licensing and copyright regulation, enabling a creator to license their own code and respecting others' licensing rights. Equally as important, code should be trustworthy and should not contain secrets.

-**Lawful**: The code respects licensing and copyright regulation.

-**Trustworthy**: The code abstains from revealing or hard-coding private information.

-**Respectful**: The code refrains from using discriminatory and offensive language.

## [What is code optimization](https://pvs-studio.com/en/blog/terms/0084/)
Code optimization is a crucial process of modifying code to enhance its quality and efficiency. It involves various techniques aimed at improving different aspects of the program, such as reducing its size, minimizing memory usage, increasing execution speed, or minimizing input/output operations.

When optimizing code, it is essential to ensure that the optimized version produces the same output and has the same side effects as its non-optimized counterpart. This requirement ensures that the functionality and behavior of the program remain intact throughout the optimization process. However, in certain cases, the potential benefits of optimization may outweigh the potential consequences of altering the program's behavior, and this requirement may be relaxed.

The goal of code optimization is to strike a balance between improving performance and maintaining the desired program behavior. By carefully evaluating the potential impact of optimizations, developers can make informed decisions to achieve the desired level of optimization without compromising the overall functionality and reliability of the program.

## [What is code refactoring](https://www.bmc.com/blogs/code-refactoring-explained/)
Code refactoring is a vital process that involves restructuring computer code without altering its external behavior or functionality. This practice aims to improve the quality, readability, and maintainability of the codebase. Refactoring can be achieved through various techniques, but it typically involves applying a series of standardized, basic actions, often referred to as micro-refactorings.

During the refactoring process, the existing source code is modified, ensuring that the software's behavior and functionality remain intact. These modifications are carefully executed in such small increments that the likelihood of introducing new errors is minimal. This approach allows developers to enhance the codebase without compromising the stability or reliability of the software.

By engaging in code refactoring, developers can achieve several benefits. It enhances code readability, making it easier for other developers to understand and maintain. Refactoring also improves the overall structure and organization of the code, making it more efficient and scalable. Additionally, it enables developers to eliminate redundant or duplicated code, reducing complexity and enhancing code maintainability.

Code refactoring is an ongoing process that should be incorporated into the software development lifecycle. By continuously refining the codebase, developers can ensure its long-term sustainability, adaptability, and ease of future enhancements or bug fixes. It is a practice that demonstrates a commitment to producing high-quality, robust software systems.

## [Continuous integration and continuous deployment (CI/CD)](https://www.atlassian.com/continuous-delivery/principles/continuous-integration-vs-delivery-vs-deployment)
 
### Continuous integration CI
Developers practicing continuous integration merge their changes back to the main branch as often as possible. The developer's changes are validated by creating a build and running automated tests against the build. By doing so, you avoid integration challenges that can happen when waiting for release day to merge changes into the release branch.
Continuous integration puts a great emphasis on testing automation to check that the application is not broken whenever new commits are integrated into the main branch.

### Continuous deployment CD
Continuous deployment goes one step further than continuous delivery. With this practice, every change that passes all stages of your production pipeline is released to your customers. There's no human intervention, and only a failed test will prevent a new change to be deployed to production.
Continuous deployment is an excellent way to accelerate the feedback loop with your customers and take pressure off the team as there isn't a "release day" anymore. Developers can focus on building software, and they see their work go live minutes after they've finished working on it.

## [What is DRY (Don't Repeat Yourself)](https://www.linkedin.com/pulse/dry-principles-react-native-rohit-bansal/)
The DRY (Don't Repeat Yourself) principle is a fundamental concept in software development that promotes code reusability and maintainability by avoiding duplication. In React Native, applying the DRY principle can greatly benefit developers in writing clean, maintainable, and scalable code.


## Applying the DRY principle in React Native
### Use reusable components:
Instead of duplicating code for similar UI elements, developers can create reusable components that can be used across the app. This can help to reduce code duplication and make the codebase more maintainable.

### Use helper functions:
Instead of duplicating code for common tasks, developers can create helper functions that can be reused across the app. This can help to reduce code duplication and make the codebase more maintainable.

### Use constants:
Instead of hardcoding values in the code, developers can use constants to define values that are used across the app. This can help to reduce code duplication and make the codebase more maintainable.

### Use inheritance and composition:
Instead of duplicating code for similar components, developers can use inheritance and composition to reuse code across components. This can help to reduce code duplication and make the codebase more maintainable.



