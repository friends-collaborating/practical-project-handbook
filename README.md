# software-project-handbook
A handbook outlining the lessons learned when starting a new project

## 1. Requirement Gathering

You need to figure out and write down what you want to achieve. *The project goal is the higest-level requirement!*
For example, I would like to create a tool to help people start software projects.

There are technical books covering languages, systems, and techniques, but very few which document how to start a project.

### Talking with stackholders

* Stakeholders are the people driving the project.
* Stakeholders define the vision and capabilities of the project.
* There are many types of stakeholder.
  * Clients and Customers
    * These are the people who pay for the project
      * via monetary means
      * via time and effort.
  * End-Users
    * The people who will interact with the software
  * Consultants/Subject Matter Experts
    * Experts in the field this software deals with 
  * Development Team
    * This includes programmers and managers 
  * Governments
    * Governments might have made laws which a software must follow. 
  * 3rd Systems the software interfaces with
    * Any thirdparty system your software interacts with has rules and limits.
      * request/second
      * dollars/month

Before jumping into a project, it is very important to consider each of these stakeholders and their impact. It is possible that at the beginning, the only stakeholder is you. If this is the case, it is still worth your time thinking about and writing down the problem you are about to solve. **Write down the purpose of the project.** For example, the purpose of this project is, *To make freely available, a community sourced stategy to best start a software project.* The purpose of a project should echo with it an advantage. There is little point in making a tool, if that tool does not solve a problem or provide an advantage in some way.

The advantage with this particular project comes when starting a new project. We can read and follow best practices, and save ourselves a lot of time.

I worked in carpentry for a few summers before I started developing software full-time. My boss at the time gave me this advice. *If you and I are doing the same task, but it takes me twice as long, it is my responsibility to ask you how to do it faster.* Talking with the stakeholders of project is not a one time deal. Requirements can change over time. It is important to update your requirements. Make sure all your team-members are aware of the updates, are able to give their feedback, and that they are well understood. This is the first part in helping your project move quickly.

### Functional requirements
 * Those requirements that cause the product to do something.

### Non-Functional requirements
 * Those requirements that specify how well the product does what it does. 

## 2. Development

### The Development Environments

* Develop against the same tools you are going to deploy against.
  * If you are going to run your application on Redhat Linux you should make sure you develop on Redhat Linux (or CENTOS).
  * Vagrant + Virtualbox makes this easier than ever before.
  * If you need a database, and for production you picked PostgreSQL, you should develop against PostgreSQL, not sqlite.
 
### The Development Process

The following are things we do and think about at the start of the development process.

* Data Modeling
* JSON Validation
* Error Handling
* Mock services
