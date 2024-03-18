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

## What is code optimization
In computer science code optimization is the process of modifying a software system to make some aspect of it work more efficiently or use fewer resources. In general, a computer program may be optimized so that it executes more rapidly, or to make it capable of operating with less memory storage or other resources, or draw less power.

## What is code refactoring
Code refactoring is defined as the process of restructuring computer code without changing or adding to its external behavior and functionality. There are many ways to go about refactoring, but it most often comprises applying a series of standardized, basic actions, sometimes known as micro-refactorings. The changes in existing source code preserve the software’s behavior and functionality because the changes are so tiny that they are unlikely to create or introduce any new errors.

## Continuous integration and continuous deployment (CI/CD)
 
### Continuous integration CI
Developers practicing continuous integration merge their changes back to the main branch as often as possible. The developer's changes are validated by creating a build and running automated tests against the build. By doing so, you avoid integration challenges that can happen when waiting for release day to merge changes into the release branch.
Continuous integration puts a great emphasis on testing automation to check that the application is not broken whenever new commits are integrated into the main branch.

### Continuous deployment CD
Continuous deployment goes one step further than continuous delivery. With this practice, every change that passes all stages of your production pipeline is released to your customers. There's no human intervention, and only a failed test will prevent a new change to be deployed to production.
Continuous deployment is an excellent way to accelerate the feedback loop with your customers and take pressure off the team as there isn't a "release day" anymore. Developers can focus on building software, and they see their work go live minutes after they've finished working on it.

## What is DRY (Don't Repeat Yourself)
DRY is an important software development principle that emphasises the importance of avoiding duplication in code. 
In React Native, the DRY principle can help developers to write clean, maintainable, and scalable code.

## Applying the DRY principle in React Native
### Use reusable components:
Instead of duplicating code for similar UI elements, developers can create reusable components that can be used across the app. This can help to reduce code duplication and make the codebase more maintainable.

### Use helper functions:
Instead of duplicating code for common tasks, developers can create helper functions that can be reused across the app. This can help to reduce code duplication and make the codebase more maintainable.

### Use constants:
Instead of hardcoding values in the code, developers can use constants to define values that are used across the app. This can help to reduce code duplication and make the codebase more maintainable.

### Use inheritance and composition:
Instead of duplicating code for similar components, developers can use inheritance and composition to reuse code across components. This can help to reduce code duplication and make the codebase more maintainable.



