# Awesome Domain-Driven Design [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 438,706 | 🐛 70 | 📅 2026-01-28 with stars

> A curated list of Domain-Driven Design (DDD), Command Query Responsibility Segregation (CQRS), Event Sourcing, and Event Storming resources.

**Check out my [blog](https://buildplease.com) and [weekly DDD newsletter](https://buildplease.com/pages/dddweekly/) or say hi on [Twitter](https://twitter.com/heynickc)!**

**[Domain-Driven Design (DDD)](https://en.m.wikipedia.org/wiki/Domain-driven_design)** is an approach to software development for complex needs by connecting the implementation to an evolving model.  The premise of Domain-Driven Design is the following:

* placing the project's primary focus on the core domain and domain logic
* basing complex designs on a model of the domain
* initiating a creative collaboration between technical and domain experts to iteratively refine a conceptual model that addresses particular domain problems

The term was coined by Eric Evans in his book of the same title.

**[Command Query Responsibility Segregation (CQRS)](http://codebetter.com/gregyoung/2010/02/16/cqrs-task-based-uis-event-sourcing-agh/)** is simply the creation of two objects where there was previously only one. The separation occurs based upon whether the methods are a command or a query (the same definition that is used by Meyer in Command and Query Separation, a command is any method that mutates state and a query is any method that returns a value).

**[Event Sourcing](http://www.martinfowler.com/eaaDev/EventSourcing.html)** the fundamental idea of Event Sourcing is that of ensuring every change to the state of an application is captured in an event object, and that these event objects are themselves stored in the sequence they were applied for the same lifetime as the application state itself.

**[Event Storming](https://ziobrando.blogspot.com/2013/11/introducing-event-storming.html)** is a workshop format for quickly exploring complex business domains.

## Contents

* [Awesome Domain-Driven Design](https://github.com/heynickc/awesome-ddd/) ⭐ 12,128 | 🐛 9 | 📅 2025-07-04
  * [Contents](#contents)
  * [Books](#books)
  * [Free eBooks](#free-ebooks)
  * [Training Courses](#training-courses)
  * [Video Collections](#video-collections)
  * [Community Resources](#community-resources)
  * [Blogs](#blogs)
  * [Sample Projects](#sample-projects)
    * [GO](#go)
    * [.NET (C#/F#)](#net-cf)
    * [Haskell](#haskell)
    * [Idris](#idris)
    * [JavaScript / TypeScript](#javascript--typescript)
    * [JVM languages](#jvm-languages)
    * [PHP](#php)
  * [Libraries and Frameworks](#libraries-and-frameworks)
    * [GO](#go-1)
    * [.NET](#net)
    * [Databases](#databases)
    * [Elixir](#elixir)
    * [JavaScript / TypeScript](#javascript--typescript-1)
    * [JVM](#jvm)
    * [PHP](#php-1)
    * [Python](#python)
    * [Ruby](#ruby)
  * [Podcasts and Interviews](#podcasts-and-interviews)
  * [Conferences](#conferences)
  * [User Groups](#user-groups)
  * [Tools](#tools)
  * [License](#license)

## Books

* [Applying Domain Driven Design with CQRS and Event Sourcing](https://buildplease.com/pages/now-what/) - A walkthrough of using EventStorming and other modeling techniques to build a CQRS and Event Sourcing-based prototype for a fictional business domain.
* [Architecture Modernization](https://www.manning.com/books/architecture-modernization) - Concrete tools, techniques, and processes to align software architecture with your business domains, organizational design, team topologies, and corporate strategy.
* [Collaborative Software Design](https://www.manning.com/books/collaborative-software-design) - A practical guide for effectively involving all stakeholders in the design of software.A practical guide for effectively involving all stakeholders in the design of software.
* [CQRS](https://leanpub.com/cqrs) - Notes by Mark Nijhof from his experiences learning DDD and CQRS from Greg Young.  There is an extensive sample project that accompanies this book.
* [Domain-Driven Design: Tackling the Complexity at the Heart of Software](https://amzn.com/0321125215) - The canonical book that coined the term Domain-Driven Design.  Also known as the "Blue Book."
* [Domain-Driven Design Distilled](https://www.amazon.com/Domain-Driven-Design-Distilled-Vaughn-Vernon/dp/0134434420) - Very good starter book before you read [Implementing Domain-Driven Design](https://vaughnvernon.co/?page_id=168#iddd) or [Domain-Driven Design: Tackling the Complexity at the Heart of Software](https://amzn.com/0321125215).
* [Domain-Driven Design in PHP](https://leanpub.com/ddd-in-php) - Real examples written in PHP showcasing DDD Architectural Styles, Tactical Design, and Bounded Context Integration.
* [Domain-Driven Rails](https://blog.arkency.com/domain-driven-rails/) - Domain-Driven Rails describes 11 techniques (from Bounded Contexts to Event Sourcing) that you can use separately and together in new and old Rails apps to achieve better architecture.
* [Domain Modeling Made Functional](https://pragprog.com/book/swdddf/domain-modeling-made-functional) - Tackle Software Complexity with Domain-Driven Design and F#.
* [Domain Specific Languages](http://martinfowler.com/books/dsl.html) - Tangentially connected to DDD, describes the importance of the Ubiquitous Language and working together with domain experts, along with lots of technical details.
* [Event Sourcing and CQRS with .NET Core and SQL Server](https://buildplease.com/products/fpc-v2/) - A walkthrough of using Domain-Driven Design with Event Sourcing and CQRS using ASP.NET Core and SQL Server in production.
* [Hands-On Domain-Driven Design with .NET Core](https://www.amazon.com/Hands-Domain-Driven-Design-NET-dp-1788834097/dp/1788834097) - Tackling complexity in the heart of software by putting DDD principles into practice by Alexey Zimarev.
* [Implementing Domain-Driven Design](https://www.amazon.com/Implementing-Domain-Driven-Design-Vaughn-Vernon/dp/0321834577) - Also a canonical book presenting a top-down approach to understanding Domain-Driven Design.  Also known as the "Red Book."
* [Implementing DDD, CQRS and Event Sourcing](https://leanpub.com/implementing-ddd-cqrs-and-event-sourcing) - Learn how to implement DDD, CQRS and Event Sourcing. Understand the theory and put it into practice with JavaScript and Node.js.
* [Introducing Event Storming: An act of Deliberate Collective Learning](https://leanpub.com/introducing_eventstorming) - The deepest tutorial and explanation about EventStorming, straight from the inventor.
* [Learning Domain-Driven Design: Aligning Software Architecture and Business Strategy](https://www.amazon.com/Learning-Domain-Driven-Design-Aligning-Architecture/dp/1098100131/) - Learn the essential patterns and practices of domain-driven design and how to apply them in your day-to-day work, both in greenfield and brownfield projects.
* [Microsoft .NET - Architecting Applications for the Enterprise (2nd Edition)](https://www.amazon.com/Microsoft-NET-Architecting-Applications-Enterprise/dp/0735685355/) - A software architect’s digest of core practices, pragmatically applied.
* [Patterns, Principles, and Practices of Domain-Driven Design (1st Edition)](https://www.amazon.com/Patterns-Principles-Practices-Domain-Driven-Design/dp/1118714709) - Methods for managing complex software construction following the practices, principles and patterns of Domain-Driven Design with code examples in C#.
* [Secure by Design](https://www.manning.com/books/secure-by-design?a_aid=danbjson\&a_bid=0b3fac80) - Shows how to use Domain-Driven Design to avoid security vulnerabilities.
* [Specification by Example](https://www.manning.com/books/specification-by-example) - This book distills from the experience of leading teams worldwide effective ways to specify, test, and deliver software in short, iterative delivery cycles. Case studies in this book range from small web startups to large financial institutions, working in many processes including XP, Scrum, and Kanban.
* [Versioning in an Event Sourced System](https://leanpub.com/esversioning) - Have you had troubles with versioning an Event Sourced system? Just getting into a new Event Sourced system for the first time? This book is the definitive guide of how to handle versioning over long periods of time.
* [What is Domain-Driven Design?](https://learning.oreilly.com/library/view/what-is-domain-driven/9781492057802/) - A quick read exploring the core patterns and principles of Domain-Driven Design, as well as strategies for applying DDD in brownfield projects.
* [Writing Great Specifications](https://www.manning.com/books/writing-great-specifications) - Writing Great Specifications is an example-rich tutorial that teaches you how to write good Gherkin specification documents that take advantage of Specification by Example's benefits.
*

## Free eBooks

* [.NET Microservices: Architecture for Containerized .NET Applications](https://dotnet.microsoft.com/download/thank-you/microservices-architecture-ebook) - An introduction to developing microservices-based applications and managing them using containers. [eShopOnContainers sample](https://github.com/dotnet-architecture/eShopOnContainers) ⚠️ Archived
* [Architecting Modern Web Applications with ASP.NET Core and Microsoft Azure](https://dotnet.microsoft.com/download/thank-you/aspnet-ebook) - Provides end-to-end guidance on building monolithic web applications using DDD, ASP.NET Core, and Azure. [eShopOnWeb sample](https://github.com/dotnet-architecture/eShopOnWeb) ⚠️ Archived
* [The Anatomy of Domain-Driven Design - The Infographic](https://leanpub.com/theanatomyofdomain-drivendesign) - An infographic on the anatomy of Domain-Driven Design.
* [Architecture Patterns with Python](https://www.cosmicpython.com/book/preface.html) - A book about Pythonic application architecture patterns for managing complexity.
* [CQRS Journey](https://msdn.microsoft.com/en-us/library/jj554200.aspx) - Exploring CQRS and Event Sourcing.
* [Domain-Driven Design: The First 15 Years](https://dddeurope.com/15years) - To celebrate the anniversary, we've asked prominent authors in the software design world to contribute old and new essays. With contributions by Martin Fowler, James Coplien, Rebecca Wirfs-Brock, Mel Conway, and many more.
* [DDD Reference](http://domainlanguage.com/wp-content/uploads/2016/05/DDD_Reference_2015-03.pdf) - A summary of the patterns and definitions of DDD.
* [Domain Driven Design Quickly](https://www.infoq.com/minibooks/domain-driven-design-quickly) - Domain Driven Design Quickly is a short, quick-readable summary and introduction to the fundamentals of DDD.
* [Effective Aggregate Design](http://dddcommunity.org/library/vernon_2011/) -  In this three-part series, Vaughn Vernon walks through some common design pitfalls, discusses the pros and cons of various aggregate modeling choices, and provides rules of thumb to guide modeling of aggregates.
* [Getting Started with DDD when Surrounded by Legacy Systems](http://domainlanguage.com/wp-content/uploads/2016/04/GettingStartedWithDDDWhenSurroundedByLegacySystemsV1.pdf) - Describes three strategies for getting started with DDD when you have a big commitment to legacy systems.
* [Living Documentation by Design, with Domain-Driven Design](https://leanpub.com/livingdocumentation) - Discover how a Living Documentation can help you in all aspects of your projects, from the business goals to the business domain knowledge, architecture and design, processes and deployment, even if you hate writing documentation.
* [The Semantic JavaScript Backend for Event-Driven Development](https://docs.wolkenkit.io/1.1.0/downloads/brochure/) - A 68 pages long free ebook on what DDD, CQRS and event-sourcing are, and how they fit each other.
* [DDD Magazine from Xebia #1](https://pages.xebia.com/domain-driven-design-magazine-xebia) - This magazine is packed with visionary and practical insights, based on personal, business, and customer experiences to support you on your DDD journey
* [Visual Collaboration Tools](https://leanpub.com/visualcollaborationtools/) - Visual Collaboration Tools is a book for teams building software. It describes tools that help us in our daily job, and also present field stories from different practitioners.

## Training Courses

* [Advanced Distributed Systems Design](https://learn-particular.thinkific.com/courses/adsd-online) - Online training course from Udi Dahan.  Udi's live training schedule can be found [here](http://udidahan.com/training/).
* [DDD Workshops across Europe and Online](https://training.dddeurope.com/) - Public Workshops by Eric Evans, Alberto Brandolini, Mathias Verraes, Rebecca Wirfs-Brock, Nick Tune, and many more.
* [DDD Workshop by Xebia](https://xebia.com/academy/en/search?query=Domain-driven%20design) - public and in-house Domain-driven design workshops from foundation to professional level.
* [Distilling Domain-Driven Design](https://www.informit.com/store/domain-driven-design-livelessons-video-training-9780134597324) - Vaughn Vernon's online training course.
* [Domain Language eLearning](http://elearn.domainlanguage.com/) - Using our video lessons with Eric Evans, author of the original book on Domain-Driven Design (DDD), teach yourself techniques for evolving practical models that improve your software — not just your documents.
* [Event Sourcery](https://www.youtube.com/@EventSourcery) - Introduction to DDD, CQRS, and Event Sourcing.
* [EventStorming Fundamentals Course](https://elearning.dsolemorera.com/courses/eventstorming-fundamentals) ([also in Spanish](https://elearning.dsolemorera.com/courses/fundamentos-eventstorming)) - learn the fundamentals of EventStorming. Everything about EventStorming with examples.
* [Greg Young's CQRS Class](http://subscriptions.viddler.com/GregYoung/) - These videos include the entirety of Greg Young's DDD, CQRS, and Event Sourcing class.
* [Mixter](https://github.com/DevLyon/mixter) ⭐ 314 | 🐛 3 | 🌐 CSS | 📅 2023-10-06 - CQRS and Event Sourcing Koans.
* [Nomad PHP](https://nomadphp.com/product/introduction-event-sourcing-cqrs/) - Introduction to Event Sourcing and CQRS.
* [Pluralsight](https://pluralsight.com)
  * [Domain-Driven Design Fundamentals](https://www.pluralsight.com/courses/domain-driven-design-fundamentals) - Teaches the fundamentals of Domain-Driven Design (DDD) through a demonstration of customer interactions and a complex demo application, along with advice from Eric Evans.
  * [Domain-Driven Design in Practice](https://www.pluralsight.com/courses/domain-driven-design-in-practice) - A descriptive, in-depth walk-through for applying Domain-Driven Design principles in practice.
  * [Modern Software Architecture: Domain Models, CQRS, and Event Sourcing](https://www.pluralsight.com/courses/modern-software-architecture-domain-models-cqrs-event-sourcing) - This course covers DDD analysis patterns helpful in discovering the top-level architecture of a business domain. Architects and developers will find details of implementation patterns such as Domain Model, CQRS, and Event Sourcing.
* [Rails + Domain Driven Design Workshop](https://blog.arkency.com/ddd-training/) - Introduction to DDD, fundamentals of CQRS & Event Sourcing for Ruby/Rails developers.
* [Reactive Architecture: CQRS and Event Sourcing](https://cognitiveclass.ai/courses/reactive-architecture-cqrs/) - This course will discuss the reasons we use CQRS/ES, what benefits it provides us, but also what it will cost us to use. We will see how CQRS/ES can impact the scalability, consistency, and availability of our application.
* [Reactive Architecture: Domain Driven Design](https://cognitiveclass.ai/courses/reactive-architecture-ddd/) - Use DDD to decompose a problem domain into manageable parts. Learn how those parts can become the foundation of Reactive Microservices and Reactive Architecture. Free, online, self-paced. Certificate offered upon completion.
* [Spatie's Event Sourcing Course](https://spatie.be/products/event-sourcing-in-laravel) - Learn how to build event sourced applications in Laravel using Spatie's event-sourcing package. Has 2 hours of video content and an accompanying ebook.

## Video Collections

* [DDD Europe](https://dddeurope.com/videos) - Recordings of talks given at DDD Europe.
* [SkillsCasts by SkillsMatter](https://skillsmatter.com/skillscasts) - Searching DDD returns various talks given by Greg Young, Alberto Brandolini, and Dan North, etc.
* [Alberto Brandolini: Event Storming](https://www.youtube.com/watch?v=veTVAN0oEkQ\&list=PLve553MhJLs4YkEnHmOjWJv0B-6WY0-JI) - A YouTube collection of talks given by Alberto Brandolini on Event Storming.
* [GlobalAppTesting TechTalks](https://vimeo.com/showcase/gatengineering) - A vimeo channel focused on DDD and CQRS.
* [Greg Young](https://www.youtube.com/watch?v=JHGkaShoyNs\&list=PL5XpN_ZVafKLePdxruDfdfi-IiZtXz-k9) - A YouTube collection of various talks given by Greg Young.
* [Explore DDD videos](https://www.youtube.com/channel/UCcpKGt6MVvz7dISXLlMGmag) - Recordings of the talks given at the Explore DDD conference.
* [KanDDDinsky](https://www.youtube.com/channel/UCJCpnslPdb_Dl8DKokXC3HA) - A YouTube collection of talks given at KanDDDinsky.
* [Virtual Domain-driven design](https://www.youtube.com/channel/UCob_jOzzpxBp-di-x0vLlwA) - A youtube collection of recorded meetups session from Virtual Domain-driven design
* [Visuality DDD webinars](https://youtube.com/playlist?list=PLvMNoWK93wtnu9JcSEYnFRgzqbxtLtZZ4) - A YouTube collection of webinars focused on DDD in Ruby on Rails
* [The Art of Discovering Bounded Contexts by Nick Tune](https://www.youtube.com/watch?v=ez9GWESKG4I) - Session from 2017 DevoxxUK on how to define bounded contexts

## Community Resources

* [Awesome Event Storming](https://github.com/mariuszgil/awesome-eventstorming) ⭐ 2,355 | 🐛 6 | 📅 2024-10-23 - awesome list that focuses only on Event Storming.
* [Context Mapping by ddd-crew](https://github.com/ddd-crew/context-mapping) ⭐ 1,770 | 🐛 8 | 📅 2025-06-22 - 	Context Mapping Cheatsheet and Starter Kit by ddd-crew.
* [Domain-Driven Design in dynamic languages GitHub](https://github.com/valignatev/ddd-dynamic) ⭐ 1,392 | 🐛 3 | 📅 2023-06-08 - GitHub's profile of Domain-Driven Design in dynamic languages.
* [Awesome Domain Storytelling](https://github.com/hofstef/awesome-domain-storytelling) ⚠️ Archived - awesome list that focuses only on Domain Storytelling.
* [Advanced Topics in Event Sourcing / CQRS / DDD](https://github.com/sebastianharko/adv-es-cqrs-ddd) ⭐ 110 | 🐛 0 | 📅 2020-04-23 - Advanced Topics in Event Sourcing / CQRS / DDD list compiled and maintaned by @[sebastianharko](https://github.com/sebastianharko).
* [DDD/CQRS/ES Discord](https://github.com/ddd-cqrs-es/community) ⭐ 77 | 🐛 2 | 📅 2022-11-28 - A Discord (old Slack) team for those who want to chat about Domain-Driven Design, CQRS, Event Sourcing and sometimes random things. Main channel is language and framework agnostic.
* [DDD/CQRS Google Group](https://groups.google.com/forum/?utm_source=digest\&utm_medium=email#!forum/dddcqrs) - An active mailing list and an excellent resource to ask questions and learn fine-grained details about DDD/CQRS.
* [DDD-es Google Group](https://groups.google.com/g/ddd-es) - The Google Group to discuss Domain-Driven Design in Spanish.
* [DDDinPHP Google Group](https://groups.google.com/forum/#!forum/dddinphp) - The place to discuss Domain-Driven Design, CQRS, Event Sourcing, Model Storming, Hexagonal Architecture, Distributed Systems, Reactive... in the context of PHP.
* [EventStorming Google Group](https://groups.google.com/g/eventstorming) - The Google Group to discuss EventStorming.
* [DDD in Ruby on Rails](https://www.visuality.pl/posts/introduction-to-ddd-in-ruby-on-rails) - A collection of articles on Domain-Driven Design in Ruby on Rails
* [DDD in Ruby subreddit](https://www.reddit.com/r/ddd_ruby/) - A subreddit for Ruby developers interested in Domain-Driven Design.
* [Domain StoryTelling Discord](https://discord.gg/KsYaHNNn33) - A Discord team about Domain StoryTelling (#domain-storytelling channel) by [@hofstef](https://twitter.com/hofstef). The homepage is at [domainstorytelling.org](http://domainstorytelling.org/).
* [Software Engineering Stack Exchange](http://softwareengineering.stackexchange.com/questions/tagged/domain-driven-design) - Software Engineering Stack Exchange questions tagged *domain-driven-design*.
* [Code Review Stack Exchange](http://codereview.stackexchange.com/questions/tagged/ddd) - Code Review Stack Exchange questions tagged *domain-driven-design*.
* [Stack Overflow](https://stackoverflow.com/questions/tagged/domain-driven-design) - Stack Overflow questions tagged *domain-driven-design*.
* [Quora](https://www.quora.com/topic/Domain-Driven-Design-DDD) - Questions tagged *domain-driven-design*.
* [wolkenkit Slack](http://slackin.wolkenkit.io/) - A Slack team on DDD, event-sourcing, CQRS and wolkenkit.
* [Virtual Domain-driven design community](https://virtualddd.com) - Online meetups with panel discussions, online collaborations and resource sharing.
* [Domain-driven design heuristics](https://www.dddheuristics.com/) - Domain-Driven Design Heuristics is a community driven site to document and discuss about Design Heuristics.
* [Domain-Driven Design Crew GitHub](https://github.com/ddd-crew) - GitHub's profile of Domain-Driven Design Crew.
* [DDD North America](https://dddna.net/) - Upcoming live training, events, and user groups across North America.

## Blogs

* [Aardling Blog](https://aardling.eu/en/insights) - DDD and software design articles from Mathias Verraes and others.
* [Nick Chamberlain](https://buildplease.com) - Helpful development and design advice for .NET developers.
* [Ardalis.com](https://ardalis.com/blog) - Steve Smith. Pluralsight author and author of [DDD Fundamentals](https://www.pluralsight.com/courses/domain-driven-design-fundamentals) course and Microsoft [eShopOnWeb sample app](https://github.com/dotnet-architecture/eShopOnWeb) ⚠️ Archived.
* [DDD Weekly](http://dddweekly.com) - Weekly curated links related to DDD/CQRS/ES.
* [Daniel Whittaker](http://danielwhittaker.me) - Want to learn about CQRS and Event Sourcing? This blog is packed with step-by-step articles to give you a head start.
* [Cyrille Martraire](http://cyrille.martraire.com) - Being so immersed in finance while still in love with programming, I’m naturally a big fan of Domain-Driven Design by Eric Evans, along with TDD, BDD and agile/XP practices.
* [Jimmy Bogard](https://lostechies.com/jimmybogard/) - I focus on DDD, distributed systems, and any other acronym-centric design/architecture/methodology.
* [CodeBetter](http://codebetter.com) - CodeBetter.Com exists in order to help foster awareness of better practices, superior tools, proven methodologies and techniques within the software development community.
* [Greg Young](https://goodenoughsoftware.net/) - Good Enough Software is By Definition Good Enough.
* [InfoQ Blog](https://www.infoq.com/domaindrivendesign/) - Domain-Driven Design Content on InfoQ.
* [Dan North](https://dannorth.net/blog/) - Inventor of Behavior-Driven Design.  Blogs and talks about Event Storming also.
* [Mike Mogosanu](http://blog.sapiensworks.com) - Maintainable code is a business advantage.  Creator of Domain Map: The Domain Modeling Tool - Easy And Powerful Domain Driven Design.
* [Christian Posta](http://blog.christianposta.com) - Principal Middleware Architect @ Red Hat, open-source enthusiast, committer @ Apache, Cloud, Integration, Kubernetes, Docker, OpenShift, Fabric8.
* [Vladimir Khorikov](http://enterprisecraftsmanship.com) - Pluralsight author.  Blogs about software development principles and best practices.
* [TechBeacon](http://techbeacon.com/) - Articles on TechBeacon tagged *domain driven design*.
* [Derek Comartin](http://codeopinion.com) - Articles under the category *Domain Driven Design*.
* [Alberto Brandolini](https://ziobrando.blogspot.it) - Inventor of Event Storming. Asserting that problems cannot be solved with the same mindset that originated them, Alberto switches perspective frequently assuming the architect, mentor, coach, manager or developer point of view.
* [Jérémie Chassaing](http://thinkbeforecoding.com/) - Various articles about DDD/CQRS.  Implemented Greg Young's SimpleCQRS sample in F#.
* [Vaughn Vernon](https://vaughnvernon.co) - Vaughn Vernon understands the unique demands of software development and the challenges you face as you improve your craft in a fast-paced industry.
* [Vladik Khononov](http://vladikk.com/) - Various DDD-related articles.
* [Eventsourcing Publications](https://blog.eventsourcing.com) - Practical event sourcing.
* [Jef Claes](http://www.jefclaes.be/) - Excellent articles and talks on Domain-Driven Design.
* [Udi Dahan](http://udidahan.com/articles/) - From the creator of NServiceBus.
* [Chris Patterson](https://lostechies.com/chrispatterson/) - From the creator of the MassTransit distributed application framework.
* [Aaron Stannard](http://www.aaronstannard.com/) - From the CTO and co-founder of Petabridge, developers of the Akka.NET Actor Model framework.
* [Roger Johansson](https://rogeralsing.com/) - Mostly C#, DDD, and Akka.NET.
* [Konrad Garus](http://squirrel.pl/blog/) - Ranting and Programming in Java, Clojure, and JavaScript.  Articles tagged under *cqrs*.
* [Oasis Digital](http://blog.oasisdigital.com/category/cqrs/) - Content by Oasis Digital tagged under *cqrs*.
* [Adaptech](http://adaptechsolutions.net/blog/) - Adaptech Solutions blog.  Our founder, Adam Dymitruk, debated the merits of CQRS with Greg Young before Greg coined the term. Adam and business partner Robert Reppel are among the leading practitioners of event-sourced microservices.
* [Lev Gorodinski](http://gorodinski.com/) - Several articles about DDD from 2013, which are still relevant.
* [Dino Esposito](https://software2cents.wordpress.com/) - Software architect, trainer, book author.  Author of [Microsoft .NET - Architecting Applications for the Enterprise (2nd Edition)](https://www.amazon.com/Microsoft-NET-Architecting-Applications-Enterprise/dp/0735685355/).
* [Dan Bergh Johnsson "Dear Junior"](http://dearjunior.blogspot.se/search/label/domain%20driven%20design) - Domain-Driven Design mixed with security, and agile in general. Written as fictional letters to a younger programmer.
* [the native web](https://www.thenativeweb.io/blog/2017-10-25-09-46-ddd-and-co-part-1-whats-wrong-with-crud/) - DDD & Co. series
* [Arkency](https://blog.arkency.com/) - Various DDD, CQRS, Event Sourcing related articles from Ruby experts.
* [Svaťa Šimara](http://svatasimara.cz/) - DDD series - language, domain, modeling, infrastructure, implementation in PHP
* [Martin Havlišta](https://xhafan.com/blog/) - DDD, CQRS, TDD blog posts with code samples in C# .NET
* [Khalil Stemmler](https://khalilstemmler.com/articles/categories/domain-driven-design) - DDD series introduction and talk about how to implement DDD with TypeScript
* [Kenny Baas-Schwegler](https://baasie.com/) - DDD, BDD, Socio-technical, EventStorming and continuous delivery blogs.
* [João Rosa](https://joaorosa.io) - Personal blog about Domain-Driven Design, Visual Collaboration, leadership and organisational design. And other things in between. Curator of [Visual Collaboration Tools](https://leanpub.com/visualcollaborationtools/) and host of the [Software Crafts Podcast](https://www.softwarecraftspodcast.com/)
* [GlobalAppTesting engineering](https://gat.engineering) - GlobalAppTesting's engineering blog with materials on practical DDD and CQRS.

## Sample Projects

### GO

* [DDD by Refactoring](https://github.com/ThreeDotsLabs/wild-workouts-go-ddd-example) ⭐ 6,189 | 🐛 30 | 🌐 Go | 📅 2025-11-03 - Complete serverless application to show how to apply DDD, Clean Architecture, and CQRS by practical refactoring of a Go project. A full blog series about it can be found at <https://threedots.tech/>.
* [Citerus DDD Sample App GO Port](https://github.com/marcusolsson/goddd) ⚠️ Archived - This is an attempt to port the [DDD Sample App](https://github.com/citerus/dddsample-core) ⭐ 5,255 | 🐛 32 | 🌐 Java | 📅 2025-06-02 to idiomatic Go. It can be run in a dockerized mode for previewing the application.
* [DDD Food App](https://github.com/victorsteven/food-app-server) ⭐ 677 | 🐛 0 | 🌐 Go | 📅 2021-12-05 - Sample DDD application implementing the 4 layers (Domain, Infrastructure, Application and Interface) and considering two domain patterns. There's a blog article written for it [here](https://dev.to/stevensunflash/using-domain-driven-design-ddd-in-golang-3ee5).
* [DDD Sample in GO](https://github.com/takashabe/go-ddd-sample) ⭐ 290 | 🐛 1 | 🌐 Go | 📅 2019-08-25 - Just another sample application implementing the four layers of DDD.
* [Evolutive CRUD API](https://github.com/friendsofgo/gopherapi) ⭐ 79 | 🐛 1 | 🌐 Go | 📅 2026-01-02 - API implementation with full CRUD using a SOLID, Hexagonal Architecture. There is a series of blog post written for it at <https://blog.friendsofgo.tech/>.
* [Simple Hexagonal Architecture PoC API](https://github.com/tomiok/patients-API) ⭐ 31 | 🐛 0 | 🌐 Go | 📅 2020-11-18 - PoC for a patients API using the hexagonal architecture pattern.
* [BDD in GO](https://github.com/JankariTech/bsDateServer) ⭐ 4 | 🐛 0 | 🌐 Go | 📅 2023-01-09 - Sample app demonstrating the use of Cucumber + GO for a BDD testing approach. Blog post can be found [here](https://dev.to/jankaritech/demonstrating-bdd-behavior-driven-development-in-go-1eci).
* [Azure DDD boilerplate](https://github.com/joshpme/azure-go-ddd-boilerplate) ⭐ 0 | 🐛 2 | 🌐 Go | 📅 2023-11-15 - A boilerplate project for DDD in Azure using a custom handler and Cosmos DB for event sourcing

### .NET (C#/F#)

* [Modular Monolith](https://github.com/kgrzybek/modular-monolith-with-ddd) ⭐ 13,385 | 🐛 67 | 🌐 C# | 📅 2024-06-04 - Full Modular Monolith .NET application with Domain-Driven Design approach.
* [eShopOnWeb](https://github.com/dotnet-architecture/eShopOnWeb) ⚠️ Archived - Full ASP.NET Core 3.1 reference application from Microsoft showing monolithic deployment architecture
* [Equinox Project](https://github.com/EduardoPires/EquinoxProject) ⭐ 6,767 | 🐛 3 | 🌐 C# | 📅 2025-06-10 - Full ASP.NET Core 3.1 application with Clean Architecture, DDD, CQRS and Event Sourcing concepts
* [Event Sourcing .NET](https://github.com/oskardudycz/EventSourcing.NetCore) ⭐ 3,645 | 🐛 23 | 🌐 C# | 📅 2026-02-19 - samples and resources about Event Sourcing and CQRS in .NET. Contains also a self-paced kit of how to built own Event Store
* [Sample .NET Core CQRS REST API](https://github.com/kgrzybek/sample-dotnet-core-cqrs-api) ⭐ 3,052 | 🐛 14 | 🌐 C# | 📅 2024-02-27 - .NET Core REST API CQRS implementation with raw SQL and DDD using Clean Architecture.
* [SimpleCQRS](https://github.com/gregoryyoung/m-r) ⭐ 2,173 | 🐛 9 | 🌐 C# | 📅 2024-02-21 - Greg Young's "Simplest Thing" CQRS with Event Sourcing project.
* [Reactive Trader Cloud](https://github.com/AdaptiveConsulting/ReactiveTraderCloud) ⭐ 1,854 | 🐛 0 | 🌐 TypeScript | 📅 2025-06-18 - Reactive Trader Cloud by Adaptive Consulting.
* [Microsoft Patterns and Practices: CQRS Journey Sample Code](https://github.com/mspnp/cqrs-journey) ⚠️ Archived - Sample code from CQRS Journey.
* [IDDD Samples in .NET](https://github.com/VaughnVernon/IDDD_Samples_NET) ⭐ 941 | 🐛 9 | 🌐 C# | 📅 2022-09-21 - These are the sample Bounded Contexts for C#.NET from the book "Implementing Domain-Driven Design" by Vaughn Vernon.
* [TaskoMask](https://github.com/hamed-shirbandi/TaskoMask) ⭐ 724 | 🐛 20 | 🌐 C# | 📅 2025-08-25 - Task management system based on .NET Core with DDD, CQRS and Event Sourcing Concepts.
* [Fohjin](https://github.com/MarkNijhof/Fohjin) ⭐ 698 | 🐛 3 | 🌐 C# | 📅 2023-07-04 - Example project that accompanies Mark Nijhof's [CQRS](https://leanpub.com/cqrs) book.
* [ContosoUniversityCore](https://github.com/jbogard/ContosoUniversityCore) ⭐ 589 | 🐛 7 | 🌐 JavaScript | 📅 2017-12-05 - ContosoUniversity on ASP.NET Core with Full .NET Framework.
* [Companion Code for Microsoft .NET Architecting Applications for the Enterprise](https://github.com/mastreeno/Merp) ⭐ 506 | 🐛 10 | 🌐 C# | 📅 2023-06-16 - An event based Micro ERP.
* [DDD-starter-dotnet](https://github.com/itlibrium/DDD-starter-dotnet) ⭐ 404 | 🐛 0 | 🌐 C# | 📅 2025-09-12 - Sample implementation and comparison of various approaches to building DDD applications. Useful as a baseline to quickly start a DDD .net project.
* [eShopOnContainersDDD](https://github.com/volak/eShopOnContainersDDD) ⭐ 322 | 🐛 30 | 🌐 C# | 📅 2023-03-04 - eShop fullstack example featuring catalog, basket, checkout, and order bounded contexts
* [Better code with DDD building blocks](https://github.com/asc-lab/better-code-with-ddd) ⭐ 321 | 🐛 0 | 🌐 C# | 📅 2025-12-10 - solution presents usage of DDD tactical patterns to achieve better readability and expressiveness of the code. Applying DDD patterns together with ubiquitous language closes the gap between language spoken by experts and the team and language used in the code.
* [TodoMVC-DDD-CQRS-EventSourcing](https://github.com/volak/TodoMVC-DDD-CQRS-EventSourcing) ⭐ 257 | 🐛 2 | 🌐 C# | 📅 2023-01-08 - Implementation of basic Todo app via tastejs/todomvc in C#/Typescript with eventsourcing, cqrs, and domain driven design
* [EventFlow.Example](https://github.com/OKTAYKIR/EventFlow.Example) ⭐ 204 | 🐛 2 | 🌐 C# | 📅 2023-03-03 - DDD, CQRS, and Event-Sourcing example and contains following technology stack: [EventFlow](https://github.com/eventflow/EventFlow) ⭐ 2,539 | 🐛 16 | 🌐 C# | 📅 2025-12-06, [EventStore](https://eventstore.com), [RabbitMQ](https://www.rabbitmq.com), [MongoDB](https://www.mongodb.com), [PostgreSQL](https://www.postgresql.org), [Docker](https://www.docker.com)
* [DDDInventoryItemFSharp](https://github.com/eulerfx/DDDInventoryItemFSharp) ⭐ 186 | 🐛 4 | 🌐 JavaScript | 📅 2021-03-02 - An idiomatic F# implementation of Domain-Driven Design
* [DDDSkeletonNet](https://github.com/andras-nemes/DDDSkeletonNet) ⭐ 181 | 🐛 0 | 🌐 C# | 📅 2014-03-31 (C#) - a .NET skeleton project to introduce the concepts of Domain Driven Design and loosely coupled layers.
* [NLayerAppV3](https://github.com/cesarcastrocuba/nlayerappv3) ⭐ 155 | 🐛 2 | 🌐 C# | 📅 2018-08-23 (.Net Core Preview 2) - a N-Layered Architecture Sample Project.
* [DotNet CQRS Intro](https://github.com/asc-lab/dotnet-cqrs-intro) ⭐ 139 | 🐛 0 | 🌐 C# | 📅 2019-07-02 - Examples of implementation CQRS with Event Sourcing - evolutionary approach (no CQRS, separate models and commands with the same model, separate models and commands with separate models, separate storage engines, event sourcing).
* [CQRS-DDD Example](https://github.com/dcomartin/DDD-CQRS-ES-Example) ⭐ 134 | 🐛 0 | 🌐 JavaScript | 📅 2014-05-01 - Domain Driven Design, CQRS, & Event Sourcing Example using GetEventStore, CommonDomain, NServiceBus, Entity Framework, SQL Server, SignalR.
* [FsUno](https://github.com/thinkbeforecoding/FsUno) ⚠️ Archived - Event sourcing implementation sample in F#.
* [Simple CQRS in F#](https://github.com/thinkbeforecoding/m-r) ⚠️ Archived - Greg Young's SimpleCQRS in F#.
* [Scritchy](https://github.com/ToJans/Scritchy) ⭐ 66 | 🐛 8 | 🌐 C# | 📅 2023-05-31 - CQRS without the Plumbing, [video](http://www.youtube.com/watch?v=5DKTFZD3hu8).
* [EmailMaker](https://github.com/xhafan/emailmaker) ⭐ 13 | 🐛 12 | 🌐 C# | 📅 2025-05-26 - Email marketing ASP.NET Core MVC and ASP.NET MVC demo app demonstrating [CoreDdd](https://github.com/xhafan/coreddd) ⭐ 71 | 🐛 24 | 🌐 C# | 📅 2026-02-13 usage
* [LexiQuest-Modular-DDD](https://github.com/ryletko/LexiQuest-Modular-DDD) ⭐ 7 | 🐛 0 | 🌐 C# | 📅 2024-11-14 - Modular application built with Clean Architecture and DDD principles which is ready to quickly get splitted into microserves.
* [Photostock CQRS-DDD Example](https://github.com/mr0zek/Photostock) ⭐ 7 | 🐛 1 | 🌐 C# | 📅 2021-12-20
* [Modular.StarterTemplate](https://github.com/ryletko/Modular.StarterTemplate) ⭐ 4 | 🐛 0 | 🌐 C# | 📅 2024-11-09 - Starter template for a modular application in Clean Architecture DDD style with synchronous interaction between modules within single transaction. Perfect for ERP applications.
* [EISK](https://github.com/eisk) - .NET CLI and VS Templates with simple use cases to build scalable applications on top of .net core with architectural best practices (DDD, onion architecture etc).
* [Example of Domain-Driven Design in F#](https://gist.github.com/swlaschin/2ad8627d0400b2ab70e9f3da08902c9d) - Example of Domain Driven Design for the game of checkers. There are two files: a scratch file with a series of designs, and a final version.

### Haskell

* [Eventuria gsd](https://github.com/Eventuria/gsd) ⭐ 53 | 🐛 2 | 🌐 Haskell | 📅 2019-07-23 - Haskell todo list reactive application with DDD, CQRS and Event Sourcing, FRP.

### Idris

* [OrderTaking](http://github.com/andorp/order-taking) ⭐ 142 | 🐛 0 | 🌐 Idris | 📅 2021-10-25 - Dependently typed implementation of the Domain Modeling Made Functional book. An example project how to formalize Bounded Context and Workflow diagram with dependent types. A NodeJS deployable demo.

### JavaScript / TypeScript

* [Over-engineered ToDo app](https://github.com/bitloops/ddd-hexagonal-cqrs-es-eda) ⭐ 1,404 | 🐛 2 | 🌐 TypeScript | 📅 2025-11-20 - Complete working example of using Domain Driven Design (DDD), Hexagonal Architecture, CQRS, Event Sourcing (ES), Event Driven Architecture (EDA), Behaviour Driven Development (BDD) using TypeScript and NestJS generated using the [Bitloops Language (BL)](https://github.com/bitloops/bitloops-language) ⭐ 358 | 🐛 76 | 🌐 TypeScript | 📅 2026-02-13.
* [Booster framework examples](https://github.com/boostercloud/booster/tree/master/docs/examples) ⭐ 441 | 🐛 287 | 🌐 TypeScript | 📅 2026-02-19 Example applications built with Booster Framework.
* [wolkenkit Sample Applications](https://docs.wolkenkit.io/latest/media/sample-applications/wolkenkit-boards/) - A collection of DDD sample applications, such as TodoMVC, a geocaching app, collaborative boards etc.

### JVM languages

* [DDD By Examples - Library](https://github.com/ddd-by-examples/library) ⭐ 5,690 | 🐛 23 | 🌐 Java | 📅 2023-07-07 - sample project of a library driven by real business requirements. Modular monolith implemented with the help od DDD, BDD, EventStorming, Example Mapping, CQRS, and more.
* [DDDSample](https://github.com/citerus/dddsample-core) ⭐ 5,255 | 🐛 32 | 🌐 Java | 📅 2025-06-02 - Sample DDD project using Spring Boot (originally hosted in <http://dddsample.sourceforge.net/>)
* [IDDD Samples](https://github.com/VaughnVernon/IDDD_Samples) ⭐ 3,911 | 🐛 36 | 🌐 Java | 📅 2023-09-09 - These are the sample Bounded Contexts from the book "Implementing Domain-Driven Design" by Vaughn Vernon.
* [DDD Leaven](https://github.com/BottegaIT/ddd-leaven-v2) ⭐ 881 | 🐛 2 | 🌐 Java | 📅 2023-12-17 - DDD-CQRS sample v2.0 project that helps you with starting out advanced domain modeling using Spring, JPA and testing.
* [Event Sourcing and CQRS Examples](https://github.com/andreschaffer/event-sourcing-cqrs-examples) ⭐ 590 | 🐛 6 | 🌐 Java | 📅 2026-02-16 - A pragmatic application of Event Sourcing and CQRS in Java with good references for common related problems, e.g. event ordering and idempotency.
* [Event Sourcing and CQRS Sample](https://github.com/pilloPl/event-source-cqrs-sample) ⭐ 477 | 🐛 1 | 🌐 Java | 📅 2018-05-22 - Sample event sourced application with Command Query Responsibility Segregation
* [Eclipse CargoTracker](https://eclipse-ee4j.github.io/cargotracker/) - This project demonstrates how you can develop applications with the Jakarta EE platform using widely adopted architectural best practices like Domain-Driven Design (DDD). [The code](https://github.com/eclipse-ee4j/cargotracker/) ⭐ 371 | 🐛 12 | 🌐 JavaScript | 📅 2026-01-26 is intended to mirror a non-trivial application that developers in the real work would work on. It attempts to demonstrate first-hand how you can use Jakarta EE to effectively meet practical enterprise concerns such as productivity, agility, testability, flexibility, maintainability, scalability and security. The project is directly based on the well known original [Java DDD sample application](https://github.com/citerus/dddsample-core) ⭐ 5,255 | 🐛 32 | 🌐 Java | 📅 2025-06-02 developed by DDD pioneer Eric Evans' company Domain Language and the Swedish software consulting company Citerus.
* [EventStormingWorkshop - Designing Cloud Native Microservices On AWS](https://github.com/humank/EventStormingWorkShop/) ⭐ 320 | 🐛 6 | 🌐 Java | 📅 2025-12-19 - A concrete sample to go through EventStorming workshop and implement DDD tactical design pattern in Java, apply AWS cloud native services to build up business Event based Coffeeshop scenario.
* [Kotlin DDD Sample](https://github.com/fabriciorissetto/kotlin-ddd-sample) ⚠️ Archived - Sample DDD/CQRS project written in Kotlin.
* [Java CQRS Intro](https://github.com/asc-lab/java-cqrs-intro) ⭐ 212 | 🐛 3 | 🌐 Java | 📅 2024-10-17 - Examples of implementation CQRS with Event Sourcing - evolutionary approach (no CQRS, separate models and commands with the same model, separate models and commands with separate models, separate storage engines, event sourcing).
* [Event Sourcing Example](https://github.com/Pragmatists/eventsourcing-java-example) ⭐ 100 | 🐛 4 | 🌐 Java | 📅 2017-05-16 - A simplified (in memory) example of Event Sourcing and CQRS implementation for Java code (modeled for banking domain use cases).
* [DDD Workshop - Project Manager](https://github.com/mkopylec/project-manager) ⭐ 63 | 🐛 0 | 🌐 Java | 📅 2023-02-02 - "Do It Yourself" DDD workshop and a sample DDD application at the same time. Based on a project managing domain.
* [Akka CQRS ES Demo](https://github.com/mdonkers/akka-cqrs-es-demo) ⚠️ Archived - Demo project to implement the CQRS and Event Sourcing patterns in Scala-Akka.
* <https://github.com/felipexw/clean-arch-ddd-intro> ⭐ 22 | 🐛 0 | 🌐 Java | 📅 2021-04-26 - Simple DDD + Clean Architecture using Micronaut.

### PHP

* [Symfony 5 DDD ES CQRS backend](https://github.com/jorge07/symfony-5-es-cqrs-boilerplate) ⭐ 1,085 | 🐛 4 | 🌐 PHP | 📅 2026-02-06 - DDD, CQRS and Event Sourcing app using Symfony and PHP 8.
* [Eric Evans DDD Cargo Sample](https://github.com/codeliner/php-ddd-cargo-sample) ⭐ 793 | 🐛 0 | 🌐 JavaScript | 📅 2018-11-06 - PHP 7 Version of the cargo sample used in Eric Evans DDD book
* [DDD Playground](https://github.com/jorge07/ddd-playground/) ⭐ 597 | 🐛 6 | 🌐 PHP | 📅 2022-02-28 - Sample implementation in PHP.
* [DDD CQRS Todo Sample](https://github.com/ferrius/ddd-cqrs-example) ⭐ 367 | 🐛 11 | 🌐 PHP | 📅 2023-02-01 - DDD CQRS ADR hexagonal architecture implementation built with PHP 7 and Symfony 5.
* [DDD Wish List](https://github.com/franzose/symfony-ddd-wishlist) ⭐ 202 | 🐛 0 | 🌐 PHP | 📅 2017-08-23 - A sample application in PHP built with Symfony 3 and Vue.js.
* [Shop Cart in PHP](https://github.com/simara-svatopluk/cart) ⭐ 108 | 🐛 0 | 🌐 PHP | 📅 2023-04-14 - Sample project that demonstrates how simple shop cart can look like. Domain objects,Doctrine integration.,TDD,layers,unit testing
* [DDD Modulith](https://github.com/janikredpandadev/ddd-modulith) ⭐ 0 | 🐛 0 | 🌐 PHP | 📅 2024-08-14 - A DDD Onion Architecture implementation with Symfony 7 as modulith.

## Libraries and Frameworks

### GO

* [Ginkgo](https://github.com/onsi/ginkgo) ⭐ 8,948 | 🐛 116 | 🌐 Go | 📅 2026-02-02 - Ginkgo builds on Go's testing package, allowing expressive Behavior-Driven Development ("BDD") style tests.
* [GoConvey](https://github.com/smartystreets/goconvey) ⭐ 8,424 | 🐛 168 | 🌐 Go | 📅 2024-07-30 - Go testing in the browser. Integrates with `go test`. Write behavioral tests in Go.
* [Godog](https://github.com/cucumber/godog) ⭐ 2,590 | 🐛 86 | 🌐 Go | 📅 2026-02-04 - Package godog is the official Cucumber BDD framework for Golang, it merges specification and test documentation into one cohesive whole, using Gherkin formatted scenarios in the format of Given, When, Then.
* [GOBDD](https://github.com/go-bdd/gobdd) ⭐ 139 | 🐛 9 | 🌐 Go | 📅 2026-02-12 - Small BDD framework for GO.

### .NET

* [MediatR](https://github.com/jbogard/MediatR) ⭐ 11,833 | 🐛 7 | 🌐 C# | 📅 2025-12-09 - Supports request/response, commands, queries, notifications and events, synchronous and async with intelligent dispatching via C# generic variance.
* [MassTransit](https://github.com/MassTransit/MassTransit) ⭐ 7,681 | 🐛 4 | 🌐 C# | 📅 2026-02-07 - Distributed Application Framework for .NET.
* [Marten](https://github.com/JasperFx/marten) ⭐ 3,335 | 🐛 32 | 🌐 C# | 📅 2026-02-19 - Postgresql as a Document Database and Event Store for .Net Applications.
* [EventFlow](https://github.com/eventflow/EventFlow) ⭐ 2,539 | 🐛 16 | 🌐 C# | 📅 2025-12-06 - Async/await first CQRS+ES and DDD framework for .NET <http://geteventflow.net/>.
* [NServiceBus](https://github.com/Particular/NServiceBus) ⭐ 2,162 | 🐛 295 | 🌐 C# | 📅 2026-02-18 - Service bus for .NET.
* [NEventStore](https://github.com/NEventStore/NEventStore) ⭐ 1,612 | 🐛 24 | 🌐 C# | 📅 2025-09-26 - A persistence library used to abstract different storage implementations when using event sourcing as storage mechanism.
* [shriek-fx](https://github.com/ElderJames/shriek-fx) ⚠️ Archived - An simple,elegant and useful Domain-Driven Design and CQRS framework developed using .NET Core 2.0.
* [SqlStreamStore](https://github.com/damianh/SqlStreamStore) ⚠️ Archived - .NET Stream Store library targeting SQL based implementations.
* [Aggregates.NET](https://github.com/volak/Aggregates.NET) ⭐ 441 | 🐛 7 | 🌐 C# | 📅 2025-05-30 - .NET event sourced domain driven design model via NServicebus and GetEventStore.
* [Streamstone](https://github.com/yevhen/Streamstone) ⭐ 402 | 🐛 10 | 🌐 C# | 📅 2026-02-14 - Event Store for Azure Table Storage.
* [AggregateSource](https://github.com/yreynhout/aggregateSource) ⭐ 259 | 🐛 9 | 🌐 C# | 📅 2022-06-22 - Lightweight infrastructure for doing eventsourcing using aggregates.
* [Cirqus](https://github.com/d60/Cirqus) ⚠️ Archived - d60 event sourcing + CQRS framework.
* [Projac](https://github.com/yreynhout/Projac) ⭐ 138 | 🐛 6 | 🌐 C# | 📅 2022-12-07 - Projac is a set of projection libraries that allow you to write projections targetting various backing stores.
* [CommandQuery](https://github.com/hlaueriksson/CommandQuery) ⭐ 109 | 🐛 2 | 🌐 C# | 📅 2026-01-29 - Command Query Separation for 🌐ASP.NET Core ⚡AWS Lambda ⚡Azure Functions ⚡Google Cloud Functions 🌐ASP.NET Web API 2
* [Xer.Cqrs](https://github.com/jeyjeyemem/Xer.Cqrs) ⭐ 103 | 🐛 2 | 🌐 C# | 📅 2018-05-29 - A simple library for creating applications based on the CQRS pattern with support for attribute routing and hosted handlers. Developed in C# targeting .NET Standard 1.0.
* [Its.Cqrs](https://github.com/jonsequitur/Its.Cqrs) ⚠️ Archived - A set of libraries for CQRS and Event Sourcing, with a Domain-Driven Design flavor.
* [CoreDdd](https://github.com/xhafan/coreddd) ⭐ 71 | 🐛 24 | 🌐 C# | 📅 2026-02-13 - Set of open-source .NET libraries helping with DDD and CQRS, with NHibernate persistence
* [Stringly.Typed](https://github.com/mission202/Stringly.Typed) ⭐ 47 | 🐛 4 | 🌐 C# | 📅 2018-11-20 - Making it easier to convert strings to/from .NET types.
* [CQRS on Azure](https://github.com/MerrionComputing/CQRSAzure) ⭐ 26 | 🐛 3 | 🌐 C# | 📅 2019-02-20 CQRS on Windows Azure.
* [ByValue](https://github.com/sm-g/ByValue) ⭐ 7 | 🐛 1 | 🌐 C# | 📅 2022-02-05 - This library helps to create ValueObjects (even with collection properties) with properly implemented equality behavior.
* [Core.EventStore](https://github.com/younos1986/Core.EventStore) ⭐ 6 | 🐛 3 | 🌐 C# | 📅 2023-03-03 - A library to facilitate communication between CommandService and QueryService. The Idea is when any event occures in commandService, it should be persisted in QueryService in MongoDb.
* [Deveel Repository](https://github.com/deveel/deveel.repository) ⭐ 3 | 🐛 3 | 🌐 C# | 📅 2025-07-23 - A simple implementation of the Repository pattern for .NET, supporting MongoDB and Entity Framework, extending the model with further utilities (caching, paging, validation, etc.).
* [Akka.NET](http://getakka.net/) - Akka.NET is a toolkit and runtime for building highly concurrent, distributed, and fault tolerant event-driven applications on .NET & Mono.
* [ABP](https://abp.io) - Successor of ASP.NET Boilerplate - ASP.NET Core based application framework to create NLayered, Domain Driven Designed web applications with a microservice focused modular architecture
* [ASP.NET Boilerplate](http://aspnetboilerplate.com/) - ASP.NET MVC, Web API and ASP.NET Core based application framework to create NLayered, Domain Driven Designed web Applications implementing best practices.
* [Cedar.CommandHandling](https://github.com/damianh/Cedar.CommandHandling) - Middleware to handling commands over HTTP; typically used in CQRS applications.
* [Dolittle](https://dolittle.com) - Build better applications with Dolittle. An Event Sourced, Microservice platform oriented around DDD with developer productivity and simplicity front and center.
* [Edument CQRS and Intentful BDD Testing Starter Kit](https://www.cqrs.nu/) - Library and tutorial for how to build CQRS/ES applications, including a BDD style testing framework.
* [MessageRouter](https://github.com/QuickenLoans/MessageRouter) - Described in this video: [The Beating Heart of CQRS, or Actor-Based Message Routing on the CLR](https://vimeo.com/171178586) by Paulmichael Blasucci at the New York F# .NET User Group.
* [NetDevPack](https://github.com/netdevpack) - A smart set of common classes and implementations to improve your development productivity using .NET (DDD, CQRS, Specification Pattern, MediatR, Validations, Notifications).

### Databases

* [Event Store](https://geteventstore.com) - The open-source, functional database with Complex Event Processing in JavaScript.
* [Eventsourcing](https://eventsourcing.com) - Business event capture and querying framework.
* [Message DB](https://github.com/message-db/message-db) ⭐ 1,650 | 🐛 24 | 🌐 Shell | 📅 2024-04-13 - Microservice Native Event Store and Message Store for Postgres. A fully-featured event store and message store implemented in PostgreSQL for Pub/Sub, Event Sourcing, Messaging, and Evented Microservices applications.
* [Serialized](https://serialized.io) - Complete platform for Event Sourcing & CQRS.

### Elixir

* [Commanded](https://github.com/slashdotdash/commanded) ⭐ 1,987 | 🐛 19 | 🌐 Elixir | 📅 2026-02-17 - Command handling middleware for CQRS/ES applications, Pure Functional Data Structures for Aggregates and Process Managers, Point-to-Point message routing, and much more in Elixir (Erlang VM) - All in Actor concurrency model.
* [eventstore](https://github.com/slashdotdash/eventstore) ⭐ 1,136 | 🐛 24 | 🌐 Elixir | 📅 2026-02-04 - CQRS event store using PostgreSQL for persistence.
* [Event Bus](https://github.com/otobus/event_bus) ⭐ 703 | 🐛 7 | 🌐 Elixir | 📅 2023-04-10 - Traceable, extendable and minimalist event bus implementation for Elixir with built-in event store and event watcher based on ETS.

### JavaScript / TypeScript

* [Node API Boilerplate](https://github.com/talyssonoc/node-api-boilerplate) ⭐ 3,361 | 🐛 18 | 🌐 TypeScript | 📅 2023-03-04 - NodeJS web API boilerplate for DDD and Clean Architecture applications.
* [cqrs.js](http://cqrs.js.org) - CQRS implementations in node.js.  Includes [node-eventstore](https://github.com/adrai/node-eventstore) ⭐ 539 | 🐛 25 | 🌐 JavaScript | 📅 2022-02-19, [node-cqrs-domain](https://github.com/adrai/node-cqrs-domain) ⭐ 270 | 🐛 19 | 🌐 JavaScript | 📅 2020-09-04, [node-eventdenormalizer](https://github.com/adrai/node-cqrs-eventdenormalizer) ⭐ 39 | 🐛 10 | 🌐 JavaScript | 📅 2020-09-04, [node-cqrs-saga](https://github.com/adrai/node-cqrs-saga) ⭐ 62 | 🐛 7 | 🌐 JavaScript | 📅 2020-09-04.
* [Bitloops Language (BL)](https://github.com/bitloops/bitloops-language) ⭐ 358 | 🐛 76 | 🌐 TypeScript | 📅 2026-02-13 - Open-source, 4th-generation, transpiled programming language that helps you write clean code, well-designed systems, and build high-quality software that is testable, auditable and maintainable using DDD and Hexagonal Architecture.
* [wolkenkit](https://www.wolkenkit.io/) - A CQRS, DDD, and event-sourcing framework for JavaScript and Node.js.
* [Booster](https://www.booster.cloud/) - A CQRS, DDD and event-sourcing open-source framework that leverages all the infrastructure and uses high-level abstractions and conventions. It help users build advanved even-driven applications letting them focus on business logic exclusively.

### JVM

* [DDDplus framework](https://github.com/funkygao/cp-ddd-framework) ⭐ 1,157 | 🐛 3 | 🌐 Java | 📅 2025-12-19 - A lightweight flexible development framework for complex business architecture based on DDD.
* [akka-ddd](https://github.com/pawelkaczor/akka-ddd) ⭐ 359 | 🐛 5 | 🌐 Scala | 📅 2025-06-01 - Reusable artifacts for building applications on top of the Akka platform following CQRS/DDDD-based approach.
* [Ahoo-Wang/Wow](https://github.com/Ahoo-Wang/Wow) ⭐ 282 | 🐛 13 | 🌐 Kotlin | 📅 2026-02-19 - A Modern Reactive CQRS Architecture Microservice development framework based on DDD and EventSourcing.
* [JESA](https://github.com/yreynhout/JESA) ⭐ 9 | 🐛 3 | 🌐 Java | 📅 2016-07-26 -  Event sourced aggregates for Java.
* [Apache Isis](https://isis.apache.org/index.html) - Apache Isis is a framework for rapidly developing domain-driven apps in Java.
* [Axon Framework](http://www.axonframework.org/) - The axon framework is focused on making life easier for developers that want to create a java application based on the CQRS principles.
* [Lagom](https://www.lagomframework.com) - The Lagom Framework is a microservices framework for the Java Virtual Machine, with APIs for the Java and Scala languages. It includes an Event Sourcing/CQRS based persistence module.
* [SeedStack's Business Framework](http://seedstack.org/docs/business/) - A set of building blocks that enable you to code business logic according to the Domain-Driven Design (DDD) approach.
* [Spine Event Engine](https://spine.io/) - a CQRS/ES framework for building cloud applications. Defines Bounded Contexts with their Commands, Events, and Entity states in Protobuf. The backend logic is written in Java, on top of the Proto-generated code. Client code in Java, JS or Dart communicates with the backend via gRPC.

### PHP

* [Broadway](https://github.com/broadway/broadway) ⭐ 1,511 | 🐛 3 | 🌐 PHP | 📅 2026-01-27 - Broadway is a (PHP) project providing infrastructure and testing helpers for creating CQRS and event sourced applications.
* [PHP Glossary](https://github.com/javanile/php-glossary) ⭐ 5 | 🐛 0 | 🌐 PHP | 📅 2024-04-15 - Apply a Term Analysis to extract domain terms vs out-of-scope terms in a DDD manner.
* [CodefyPHP Framework](https://github.com/codefyphp/) - A PHP framework for codefying and building complex applications using Domain-Driven Design, CQRS, and Event Sourcing.
* [Ecotone](http://ecotone.tech) - Enables message driven architecture in PHP and provides building blocks to follow DDD and CQRS principles.

### Python

* [Eventsoucing in Python](https://github.com/johnbywater/eventsourcing) ⭐ 1,634 | 🐛 2 | 🌐 Python | 📅 2026-02-15 - Mature, stable Python library for event sourcing and DDD. Supports wide variety of databases, different kinds of orderings of domain events, application level encryption, snapshotting, optimistic concurrency control, and process events. Applications, and entire systems of applications, can be defined independently of infrastructure, and run in different ways (single threaded, multi-threaded, clocked, stepping, multi-process, actor model) and with different infrastructure.
* [PyAssimilator](https://github.com/knucklesuganda/py_assimilator/) ⭐ 216 | 🐛 2 | 🌐 Python | 📅 2024-12-30 - Quickly create DDD Python patterns, Event-Based Systems, CRUD applications. Set of Python patterns for database access that support SQLAlchemy, MongoDB, Redis, or Pure Python. PyAssimilator allows you to write code without dependencies, meaning you can switch SQL to NoSQL without changing a single file in your system.
* [dry-python](https://github.com/dry-python) - A set of libraries for pluggable business logic components.

### Ruby

* [Eventide](https://eventide-project.org) - Event Sourcing and Microservices Stack for Ruby. A set of libraries for writing event driven, autonomous services.
* [Rails Event Store](https://railseventstore.org) - Rails Event Store (RES) is a library for publishing, consuming, storing and retrieving events. It's your best companion for going with an event-driven architecture for your Rails application.

## Podcasts and Interviews

* [Deeper into DDD on DotNetRocks with David Real](http://dotnetrocks.com/?show=1151) - 11 June 2015.
* [Thinking in DDD on DotNetRocks with Julie Lerman and Steve Smith](http://dotnetrocks.com/?show=1023) - 19 August 2014.
* [Eric Evans on Domain Driven Design on DotNetRocks](http://dotnetrocks.com/?show=236) - 10 May 2007.
* [Jimmy Nilsson on Domain Driven Design on DotNetRocks](http://dotnetrocks.com/?show=191) - 29 August 2006.
* [Being the Worst](http://www.beingtheworst.com) - 2012 thru 2016.
* [Software Engineering Radio Episode 225: Eric Evans on Domain-Driven Design at 10 Years](http://www.se-radio.net/2015/05/se-radio-episode-226-eric-evans-on-domain-driven-design-at-10-years/) - 13 May 2015.
* [Software Engineering Radio Episode 218: Udi Dahan on CQRS (Command Query Responsibility Segregation)](http://www.se-radio.net/2015/01/episode-218-udi-dahan-on-cqrs-command-query-responsibility-segregation/) - 30 January 2015.

## Conferences

* [Domain-Driven Design Europe](https://dddeurope.com) - The Leading DDD conference (online during COVID19)
* [EventSourcing](https://dddeurope.com/2020/#eventsourcing) - A new event for the CQRS/EventSourcing community
* [DDD Foundations](https://dddeurope.com/2020/#foundations) - A curated conference for DDD newcomers
* [Explore DDD - USA](http://exploreddd.com/)
* [Kandddinsky - Germany](http://kandddinsky.com/)

## User Groups

* [Collective CFP](https://sessionize.com/ddd-meetups) - Submit your talks to all the DDD user groups at once.
* [Map of user groups in Europe](https://datawrapper.dwcdn.net/9FNZI/)
* [Map of user groups in North America](https://datawrapper.dwcdn.net/nbZkd/)
* [Map of user groups in Asia](https://datawrapper.dwcdn.net/oin66/)
* [Map of user groups in Africa](https://datawrapper.dwcdn.net/yaEOa/)
* [Virtual](https://virtualddd.com/)
* [Worldwide](https://www.meetup.com/worldwide-eventstorming-meetup/) - Specific about EventStorming
* [Austria](https://www.meetup.com/ddd-vienna/)
* [Barcelona](https://www.meetup.com/dddbcn/)
* [Belfast](https://dddbelfast.com/)
* [Belgium](http://www.meetup.com/dddbelgium/)
* [Berlin](http://www.meetup.com/Domain-Driven-Design-Berlin/)
* [Cologne/Bonn](https://www.meetup.com/Domain-Driven-Design-Koln-Bonn/)
* [Copenhagen](https://www.meetup.com/copenhagen-domain-driven-design-meetup/)
* [Cracow](http://www.meetup.com/ddd-krk/)
* [DDD Taiwan Community](https://www.facebook.com/groups/dddtaiwan/)
* [Denver](https://www.meetup.com/ddd-denver/)
* [Iran](https://t.me/ddd_iran/)
* [Greece](https://www.meetup.com/dddgreece/)
* [Hamburg](https://www.meetup.com/DDD-HH-Domain-driven-Design-Hamburg/)
* [London](http://www.meetup.com/dddlondon/)
* [Munich](https://www.meetup.com/Microservices-Meetup-Munich/)
* [Nederland](http://www.meetup.com/Domain-Driven-Design-Nederland/)
* [Norway](https://www.meetup.com/dddnorway/)
* [Phoenix](https://www.meetup.com/DDD-Phoenix)
* [Warsaw](https://www.meetup.com/DDD-WAW)
* [Wroclaw](http://www.meetup.com/DDD-WRO)
* [Russia](https://t.me/dddevotion)

## Tools

* [Domain Storytelling](http://www.domainstorytelling.org/) - a knowledge-crunching technique that helps the people involved to familiarize themselves with the domain and work out a model that expresses their shared understanding. Available as a [print-out template](http://www.domainstorytelling.org/images/DST_Whiteboard-Kit.pdf), as well as open-source online tool, [WPS Modeler](https://www.wps.de/modeler) ([source](https://github.com/wps/domain-story-modeler) ⭐ 821 | 🐛 23 | 🌐 TypeScript | 📅 2026-02-01).

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Nick Chamberlain](https://buildplease.com) has waived all copyright and related or neighboring rights to this work.
