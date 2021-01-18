# Software Engineering Principles



## Basics
### KISS
### YAGNI
### DRY
### Don't reinvent the wheel
### Measure and monitor
### SOLID
#### Single responsibility
#### Open-closed
#### Liskov substitution
#### Interface segregation
#### Dependency inversion
### Least
#### Astonishment
#### Effort
#### Knowledge
##### Encapsulation
### Economics
#### Opportunity cost
#### Last responsible moment
##### Proof of concepts
#### Bring the pain forward




## Problem solving
### Strategies
#### Top-down
#### Bottom-up
#### Divide and conquer
### Visualize the goal
### Build iteratively
#### Feedback loops
##### Shift left
#### Crawl, walk, run
#### Work, right, pretty




## Features
### ROI
### MVP
### When in doubt, leave it out




## Separation of concerns
### Bounded contexts
### Abstraction
#### Generality
#### Don't mix different levels of abstraction
### Modularity
#### Functional independence
##### Cohesiveness
###### Anticipation of change
###### Build to change over build to last
##### Coupling
###### Dependencies
####### Minimize them
####### Make them explicit
####### Minimize probability of cascading failures
### Information hiding
#### Encapsulation
#### API
##### Hyrum's Law




## Programming
### Functional
#### Pure functions
##### Immutability
###### Shallow vs deep copies
##### Referential transparency
##### No side effects
#### Composition
#### Partial application
##### Currying
#### Higher order functions
### Composition over inheritance
### Boy-scout rule
### Conventions
#### Methods
##### Named after what they do with a verb
##### Do only one thing
#### Data comes last in signature



## Performance
### Mechanical Sympathy
### Know your latencies



## Concurrency
### Distributed Systems
- [Introduction](https://www.the-paper-trail.org/post/2014-08-09-distributed-systems-theory-for-the-distributed-systems-engineer/) (Henry Robinson)
- [Distributed systems course](https://www.cst.cam.ac.uk/teaching/2021/ConcDisSys), [lecture](https://www.youtube.com/playlist?list=PLeKd45zvjcDFUEv_ohr_HdUFe97RItdiB), [notes](https://www.cl.cam.ac.uk/teaching/2021/ConcDisSys/dist-sys-notes.pdf) (Dr. Martin Kleppmann)

#### Fallacies
- [Fallacies of distributed computing](https://en.wikipedia.org/wiki/Fallacies_of_distributed_computing)

#### CAP theorem
- [Towards robust distributed systems](https://people.eecs.berkeley.edu/~brewer/cs262b-2004/PODC-keynote.pdf) (Dr. Eric A. Brewer)
- [Brewer's conjecture and the feasibility of consistent, available, partition-tolerant web services](https://users.ece.cmu.edu/~adrian/731-sp04/readings/GL-cap.pdf) (Seth Gilbert & Nancy Lynch)
- [The CAP FAQ](https://www.the-paper-trail.org/page/cap-faq/) (Henry Robinson)
- [A critique of the CAP theorem](https://martin.kleppmann.com/2015/09/17/critique-of-the-cap-theorem.html) (Dr. Martin Kleppmann)

#### Delivery Guarantees
##### Exactly-once is hard
##### At-least-once is good enough when combined with Idempotence
##### At-most-once is good enough when loss is acceptable



## Testing
### Test desiderata
Test desired properties as described in [TestDesiderata](https://github.com/KentBeck/TestDesiderata/blob/master/index.md) (Kent Beck).
- Automated
- Specific: One reason to fail
- Deterministic
- Isolation
- Composition
- Provides confidence
- Fast execution
- Writeable: Cheap
- Readable: Descriptive
- Behavioral: Sensitive to behavior change
- Structure insensitive
- Predictive



## Time management
### Eisenhower's urgent vs important
- [Eisenhower's matrix](https://www.eisenhower.me/eisenhower-matrix) (Dwight D. Eisenhower)



## Data Engineering



## Ownership



## Collaboration
