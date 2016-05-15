# The Verification of a Distributed System
Accompanying Repository for The Verification of a Distributed System Talk to be given at [GOTO Chicago 2016](http://gotocon.com/chicago-2016)

## Abstract
Distributed Systems are difficult to build and test for two main reasons: partial failure & asynchrony.  These two realities of distributed systems must be addressed to create a correct system, and often times the resulting systems have a high degree of complexity.  Because of this complexity, testing and verifying these systems is critically important.  In this talk we will discuss strategies for proving a system is correct, like formal methods, and less strenuous methods of testing which can help increase our confidence that our systems are doing the right thing.

## References
* [The Verification of a Distributed System](http://queue.acm.org/detail.cfm?id=2889274)
* [Specifying Systems](http://research.microsoft.com/en-us/um/people/lamport/tla/book-02-08-08.pdf)
* [Use of Formal Methods at Amazon Web Services](http://research.microsoft.com/en-us/um/people/lamport/tla/formal-methods-amazon.pdf)
* [Simple Testing Can Prevent Most Critical Failures](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-yuan.pdf)
* Property Based Testing
 * [Haskell: Quick Check](https://hackage.haskell.org/package/QuickCheck)
 * [Erlang: Quick Check](http://www.quviq.com/products/erlang-quickcheck/)
 * [Other Quick Check Implementations](https://en.wikipedia.org/wiki/QuickCheck)
 * [ScalaCheck](https://www.scalacheck.org/)
 * [29 GIFs only ScalaCheck Witches will Understand](http://nerd.kelseyinnis.com/blog/2015/01/14/29-GIFs-only-scalacheck-witches-will-understand/)
 * [Quick Checking Riak](https://skillsmatter.com/skillscasts/4505-quickchecking-riak)
 * [Testing Eventual Consistency in Riak](https://www.youtube.com/watch?v=x9mW54GJpG0)
 * [Combining Model Checking and Testing](http://research.microsoft.com/pubs/200544/main.pdf)
* Fault Injection
 * [Jepsen](http://jepsen.io/)
 * [Netflix Simian Army](http://techblog.netflix.com/2011/07/netflix-simian-army.html)
 * Game Days
    * [Resilience Engineering: Learning to Embrace Failure](https://queue.acm.org/detail.cfm?id=2371297)
    * [Game Day Exercises at Stripe: Learning from `kill-9`](https://stripe.com/blog/game-day-exercises-at-stripe)
* Areas of Research
 * [Cause I'm Strong Enough: Reasoning about Consistency Choices in Distributed Systems](https://pages.lip6.fr/Marc.Shapiro/papers/CISE-POPL-2016.pdf) 
 * [IronFleet: Proving Practical Distributed Systems Correct](http://research.microsoft.com/apps/pubs/default.aspx?id=255833)
   * [Dafny](http://research.microsoft.com/en-us/projects/dafny/)
 * Lineage-Driven Fault Injection aka Molly
    * [Lineage-Driven Fault Injection](http://people.ucsc.edu/~palvaro/molly.pdf)
    * [Automated Failure Testing at Netflix](http://techblog.netflix.com/2016/01/automated-failure-testing.html)
    * [Netflix picks up Molly at University, scores harsh character assessment](http://www.theregister.co.uk/2016/02/01/netflix_tries_molly_in_quest_for_enhanced_fault_finding_perception/)
 * [Towards Property Based Consistency Verification](http://www.eurecom.fr/fr/publication/4874/download/ds-publi-4874.pdf)


## Bio
Caitie McCaffrey is a Backend Brat and Distributed Systems Diva at Twitter, where she is the Tech Lead of the Observability Team.  Prior to that she spent the majority of her career building large scale services and systems that power the entertainment industry at 343 Industries, Microsoft Game Studios, and HBO.  Caitie has a degree in Computer Science from Cornell University, and has worked on several video games including Gears of War 2, Gears of War 3, Halo 4, and Halo 5 She maintains a blog at  CaitieM.com  and frequently discusses technology on Twitter @Caitie
