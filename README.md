# [SymfonyCon - Paris 2022](https://live.symfony.com/2022-paris-con/) talks

- All talks are in **english**.
- You can send feedback and love to speakers on their twitter account
- See [all tweets](https://twitter.com/search?q=(%23symfonycon%20OR%20%23symfonycon2022)%20until%3A2022-11-19%20since%3A2022-11-17%20-%23LuckyWebby&src=typed_query&f=top) during the event

## Keynote

~~Slides~~  
~~Video~~

By [Fabien Potencier](https://connect.symfony.com/profile/fabpot)  
![github](icon/github.png) [@fabpot](https://github.com/fabpot)  
![twitter](icon/twitter.png) [@fabpot](https://twitter.com/fabpot)

---

## From monolith to decoupled…wait, why is that one getting bigger?!?

<dl>
  <dt>Description</dt>
  <dd>Monolithic apps are getting broken down left and right into dedicated services and teams, all under the banners of separating concerns, higher efficiency, and more. The strategy that is implemented will be crucial to ensure decoupling is a beacon of efficiency and not a migration nightmare.

In this talk, we’ll discuss how decoupling following the strangler fig approach will seem counter-intuitive, as your monolith continues to grow alongside your new decoupled architecture. But this approach, when done right, makes dismantling a monolith a process that is structured and safe, slow but agile, and without major service interruptions or massive interface changes that shock and discombobulate users. We will look at the experience of Platform.sh’s customer experience engineering team who are midstream on moving from a monolith to a decoupled suite of mircroservices that support every aspect of user interaction with our products.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Shawna Spoor](https://connect.symfony.com/profile/shawnaspoor)  

---

## GNAP: The future of OAuth

<dl>
  <dt>Description</dt>
  <dd>OAuth 2 is an industry-standard for authorization that every developer probably heard about.
As hinted by its name, it is the evolution of OAuth 1 and as such; it aims to address most of its known issues.

But, just like OAuth 1, OAuth 2 now has a lot of known issues.
Fortunately, a lot of these issues have been already fixed by extending the specification. The drawback of this is that today, in order to get OAuth2 right, one needs to read a dozen of RFCs and make sure they are relevant to the use case. This hurts developer experience as it increases the complexity of the protocol, which goes against its main focus: simplicity for client developers.

Here comes GNAP (Grant Negotiation and Authorization Protocol): an in-progress effort to develop the next-generation authorization protocol by learning from the past.

In this talk, we'll have a deep look into the GNAP protocol, passing by a review of the known OAuth2 flaws that it aims to fix, how it plays with authentication protocols such as Open ID Connect or WebAuthN, what is its current state and more.</dd>
</dl>

[Slides](https://slides.com/chalasr/gnap-the-future-of-oauth-2fefdf)  
~~Video~~

By [Robin Chalas](https://connect.symfony.com/profile/chalas_r)  
![github](icon/github.png) [@chalasr](https://github.com/chalasr)  
![twitter](icon/twitter.png) [@chalas_r](https://twitter.com/chalas_r)

---

## Dilemmas and decisions. What we've learned designing new Sylius API

<dl>
  <dt>Description</dt>
  <dd>Sylius and API Platform integration is the project that we started in early 2020. Since then, we were working hard designing, delivering and adjusting our new API. We've learned a lot and during my presentation, I would like to share our findings.

Why did we design our API this way?
What were our heuristics and what did we achieve?
How to design more complicated flows in API?</dd>
</dl>

[Slides](https://www.slideshare.net/ukaszChruciel1/symfonycon-dilemmas-and-decisionspdf)  
~~Video~~

By [Łukasz Chruściel](https://connect.symfony.com/profile/lchrusciel)  
![github](icon/github.png) [@lchrusciel](https://github.com/lchrusciel)  
![twitter](icon/twitter.png) [@lukaszchrusciel](https://twitter.com/lukaszchrusciel)

---

## Transactional vs. Analytical Processing

<dl>
  <dt>Description</dt>
  <dd>When it comes to the design of your Symfony application, data plays a central role. From an architectural point of view there are two common ways this data is processed. Transactional processing ensures that changes to your data are consistent and safe. Analytical processing aims to make even complex queries fast and efficient.
We should always consider the nature of processing while implementing our application’s use cases. So let's have a look at the main criterias, strategies and trade offs that will help us to navigate through all the options we have and see how we can bring your own data warehouse to life in your Symfony application leveraging tools like Doctrine, Messenger and more.</dd>
</dl>

[Slides](https://speakerdeck.com/el_stoffel/transactional-vs-analytical-processing)  
~~Video~~

By [Christopher Hertel](https://connect.symfony.com/profile/chertel)  
![github](icon/github.png) [@chr-hertel](https://github.com/chr-hertel)  
![twitter](icon/twitter.png) [@el_stoffel](https://twitter.com/el_stoffel)

---

## Customer Trust: Lessons Learned From 1000 Cybersecurity Assessments

<dl>
  <dt>Description</dt>
  <dd>Cyber crime is expected to exceed $10 Trillion globally by 2025. As a result, security compliance initiatives like SOC 2, ISO 27001, and PCI are table stakes to earn customer trust in today's market. If customer trust is important to your business, we will reveal lessons learned from over 1000 cybersecurity assessments and what you can do to stay ahead of the market's evolving security and compliance requirements.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Christian Hyatt](https://connect.symfony.com/profile/christianhyatt)  
![github](icon/github.png) [@christianhyatt](https://github.com/christianhyatt)  
![twitter](icon/twitter.png) [@christianhyatt](https://twitter.com/christianhyatt)

---

## Unleashing the power of lazy objects in PHP 🪄

<dl>
  <dt>Description</dt>
  <dd>Lazy-objects are a bit magical. They are created empty and populate themselves on-demand. They are useful when an object is heavy to instantiate but is not always used, like for example Doctrine entities or Symfony lazy-services.

But do you know how they work internally? In this talk, I'll tell you about the mechanisms provided by PHP to enable such use cases 🧙. Because doing this sort of wizardry is not common practice, I'll also introduce you to two new traits that package those lazy-loading behaviors introduced in Symfony 6.2: one for virtual inheritance proxies, and one for ghost objects 👻.

While lazy objects used to require complex code generation, these new traits make it way easier to leverage them, opening up possible innovations; lazy arguments, lazy properties, or by-design lazy classes to name a few ones. What will you come up with? Let me know after you've seen this talk!</dd>
</dl>

[Slides](https://speakerdeck.com/nicolasgrekas/unleashing-the-power-of-lazy-objects-in-php)  
~~Video~~

By [Nicolas Grekas](https://connect.symfony.com/profile/nicolas-grekas)  
![github](icon/github.png) [@nicolas-grekas](https://github.com/nicolas-grekas)  
![twitter](icon/twitter.png) [@nicolasgrekas](https://twitter.com/nicolasgrekas)

---

## Observability tools: Who's who?

<dl>
  <dt>Description</dt>
  <dd>When it comes to application observability, different categories of tools are at our disposal: static code analyzers, profilers, APMs, to name a few. Like any good tool, they usually serve a specific purpose. In this presentation, we will explore the differences between these tools, to whom they're dedicated, and see how complementary they are.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Jérôme Vieilledent](https://connect.symfony.com/profile/lolautruche)  
![github](icon/github.png) [@lolautruche](https://github.com/lolautruche)  
![twitter](icon/twitter.png) [@jvieilledent](https://twitter.com/jvieilledent)

---

## Advanced Git magic

<dl>
  <dt>Description</dt>
  <dd>You know your local from your origin, your push from your pull, your merge from your rebase. But Git is still a mystery sometimes. Making mistakes is scary. What the $^@#! is a detached HEAD state? How do you get out of it? This and more mythical Git beasts will be discovered and tamed in this tutorial.

Even advanced Git users will leave this tutorial with new skills. You’ll be force pushing, hard resetting, and auto-bisecting like nobody’s business. What’s more: you’ll be confident, comfortable, and love doing it!</dd>
</dl>

~~Slides~~  
~~Video~~

By [Pauline Vos](https://connect.symfony.com/profile/paulinevos)  
![github](icon/github.png) [@paulinevos](https://github.com/paulinevos)  
![twitter](icon/twitter.png) [@vanamerongen](https://twitter.com/vanamerongen)

---

## 7 Lessons You Can Learn From Disney Movies

<dl>
  <dt>Description</dt>
  <dd>We all love Disney movies, right? They are entertaining, trigger emotional response but also contain a lot of important lessons. And these lessons can also be applied to your career as a developer. During this talk I'll have a look at 7 situations from some of my favorite Disney movies to analyze and see what lesson we can learn from that.</dd>
</dl>

[Slides](https://speakerdeck.com/skoop/7-lessons-you-can-learn-from-disney-movies-symfonycon-2022)  
~~Video~~

By [Stefan Koopmanschap](https://connect.symfony.com/profile/skoop)  
![github](icon/github.png) [@skoop](https://github.com/skoop)  
![twitter](icon/twitter.png) [@skoop](https://twitter.com/skoop)  
![mastodon](icon/mastodon.png) [@skoop@phpc.social](https://phpc.social/@skoop)

---

## Schrödinger's SQL - The SQL inside the Doctrine box

<dl>
  <dt>Description</dt>
  <dd>Why should someone care about SQL, when a developer can abstract it with Symfony and Doctrine into PHP code? With Doctrine the database is out of sight, the database is out of mind, but this is where problems can start. What impacts are there for a Symfony project and how can they be managed? This talk handles Doctrine's behaviour and how it can influence a database and queries, why SQL is still relevant despite having an ORM and how developers can influence SQL performance.</dd>
</dl>

[Slides](https://senseexception.github.io/schroedingers-sql/symfonycon22/)  
~~Video~~

By [Claudio Zizza](https://connect.symfony.com/profile/senseexception)  
![github](icon/github.png) [@SenseException](https://github.com/SenseException)  
![twitter](icon/twitter.png) [@SenseException](https://twitter.com/SenseException)

---

## PHPStan: Advanced Types

<dl>
  <dt>Description</dt>
  <dd>To develop safer and more reliable applications, we don't have to wait for progress in PHP language itself anymore. Plenty of advanced concepts known from other languages like generics, precise array shapes, or number ranges can be expressed in PHPDocs and verified by static analysis.

In this talk I'll introduce the new types that have recently been added to PHPStan and show you how to use them in practice.

You will learn:

* How you can use PHPDocs to provide and document extra type information to static analysers, IDEs, and developers working with your code.
* Advanced types that don't yet exist natively in PHP, but can be used in PHPDocs for developing of more type-safe codebase
* Type theory about union vs. intersection types</dd>
</dl>

~~Slides~~  
~~Video~~

By [Ondřej Mirtes](https://connect.symfony.com/profile/mirtes)  
![github](icon/github.png) [@ondrejmirtes](https://github.com/ondrejmirtes)  
![twitter](icon/twitter.png) [@OndrejMirtes](https://twitter.com/OndrejMirtes)

---

## Build apps, not platforms: operational maturity in a box

<dl>
  <dt>Description</dt>
  <dd>Delivering applications today means being a part of a clearly defined and secure lifecycle – something that validates revisions on provisioned infrastructure and monitors production continuously. Organizations grow “platform teams” to manage this complexity, defining and enforcing operational standards around a common platform built in-house that connects a number of tools and providers.

This can turn into an expensive moving target, one that’ll leave your team reinventing the wheel forever – spending less time on writing features as you focus on everything else around applications. Platform.sh provides a unified, secure platform powered by Git and an infrastructure abstraction that provides operational maturity out-of-the-box. You’ll spend less time orchestrating all of your apps, and more time experimenting with new technologies, optimizing your code, and scaling all in one place.</dd>
</dl>

[Slides](https://archive.org/download/symfony-con-bat-con-presentation-ori-pekelman/SymfonyCon_BatCon%20Presentation%20Ori%20Pekelman.pdf)  
~~Video~~

By [Ori Pekelman](https://connect.symfony.com/profile/oripekelman)  
![github](icon/github.png) [@OriPekelman](https://github.com/OriPekelman)  
![twitter](icon/twitter.png) [@OriPekelman](https://twitter.com/OriPekelman)

---

## Symfony & Hotwire: an efficient combo to quickly develop complex applications

<dl>
  <dt>Description</dt>
  <dd>In December 2020, Basecamp released their first official version of the Hotwire suite. Combining the historic Turbolinks library with their Stimulus js micro-framework, it comes out a powerful combo for making complex applications while coding a fullstack Rails app. The Symfony team was quick to port the project to their ecosystem, and the results are amazing!

At Windoo we've been using the package symfony/ux-turbo suite since early 2021 to progressively replace our React legacy code. We've learned a lot about how to use it, the good practices to follow, the mistakes to avoid, and the tricky use cases to solve.

Forms, messaging, modals, asynchronous... I will show you very concrete applications of this library in your projects!</dd>
</dl>

[Slides](https://speakerdeck.com/florentdestremau/symfony-and-hotwire-an-efficient-combo-to-quickly-develop-complex-applications)  
~~Video~~

By [Florent Destremau](https://connect.symfony.com/profile/florentdestremau)  
![github](icon/github.png) [@florentdestremau](https://github.com/florentdestremau)  
![twitter](icon/twitter.png) [@FloDestremau](https://twitter.com/flodestremau)

---

## Building a great product means designing for your users

<dl>
  <dt>Description</dt>
  <dd>What makes a successful product? Is it something that looks good, works good or is it something much more simple. Delivering something that your users actually want, in an enjoyable way.
In today’s overpopulated tech space, there’s an app or site for everything. But, like you, I could tell you my most used apps on just one hand. These are the products that make what I need to do seamless and enjoyable. User centered-design aims to balance the needs of a business, while working within the capacities of your engineering team. This talk will share ways in which you can bring your user's voice to the forefront of product development through user-centered design.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Natalie Harper](https://connect.symfony.com/profile/nananat)  
![github](icon/github.png) [@nananat](https://github.com/nananat)  
![twitter](icon/twitter.png) [@nanna_nat_](https://twitter.com/nanna_nat_)

---

## The PHP Stack’s Supply Chain

<dl>
  <dt>Description</dt>
  <dd>All modern software is built using third-party software components, which may come with their own dependencies. Do you know everything about the components that make up the foundation of your software? What is the PHP software stack’s supply chain? In this presentation, Sebastian Bergmann paints a picture as complete as possible, covering topics from software supply chain security concerns to the funding of Open Source software development.</dd>
</dl>

[Slides](https://thephp.cc/presentations/2022-symfonycon-disneyland-paris-the-php-stacks-supply-chain.pdf)  
~~Video~~

By [Sebastian Bergmann](https://connect.symfony.com/profile/sebastian_bergmann)  
![github](icon/github.png) [@sebastianbergmann](https://github.com/sebastianbergmann)  
![twitter](icon/twitter.png) [@s_bergmann](https://twitter.com/s_bergmann)  
![mastodon](icon/mastodon.png) [@sebastian@thephpcc.social](https://thephpcc.social/@sebastian)

---

## FrankenPHP: a modern application server for Symfony apps

<dl>
  <dt>Description</dt>
  <dd>FrankenPHP is a modern application server for PHP built in Go. FrankenPHP gives superpowers to your PHP apps: Early Hints, worker mode, real-time capabilities, automatic HTTPS, HTTP/2 and HTTP/3 support...

How does Symfony fit with FrankenPHP? What benefits does it bring to the Symfony ecosystem?

Symfony Runtime, Symfony HttpFoundation, Symfony Mercure, Symfony Local Web Server... let's see how the Symfony ecosystem can leverage FrankenPHP for the sake of performance and simplicity!</dd>
</dl>

~~Slides~~  
~~Video~~

By [Kévin Dunglas](https://connect.symfony.com/profile/dunglas)  
![github](icon/github.png) [@dunglas](https://github.com/dunglas)  
![twitter](icon/twitter.png) [@dunglas](https://twitter.com/dunglas)  
![mastodon](icon/mastodon.png) [@dunglas@mastodon.social](https://mastodon.social/@dunglas)

---

## Panel: how Platform.sh agency partners drive innovation and growth

<dl>
  <dt>Description</dt>
  <dd>In this session, successful Platform.sh agency partners share how the Platform.sh Partner Program has helped them develop, accelerate, and scale their businesses in multiple domains, including collaboration, e-commerce, FleetOps, not-for-profit, and public sector. Partners will discuss their lessons learned and their vision for future innovations. Join us to gain insight into the latest resources available to help digital agencies drive and deliver results faster than ever before.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Erik Evrard](https://connect.symfony.com/profile/erikevrard)  
![twitter](icon/twitter.png) [@erikevrard](https://twitter.com/erikevrard)

---

## A self-training journey to the Symfony Certification - and beyond

<dl>
  <dt>Description</dt>
  <dd>When I first considered the Symfony Certification, I had no idea where to start. After freaking out in front of that huge mountain, I realized that I just needed a good roadmap to start climbing!

We’re gonna talk methodology, tools, timeline, resources. No magic recipes, only tips and tricks that helped me figure out the path to the final exam. And then I’ll explain how all of this can be applied to *any* self-training need.</dd>
</dl>

[Slides](https://archive.org/download/sfcon2022_a-self-training-journey-to-the-symfony-certification/A.self.training.journey.pdf)  
~~Video~~

By [Camille Jouan](https://connect.symfony.com/profile/ca-jou)  
![github](icon/github.png) [@Ca-Jou](https://github.com/Ca-Jou)  

---

## Fighting impostor syndrome: a practical handbook

<dl>
  <dt>Description</dt>
  <dd>If you’ve never heard about impostor syndrome, you might realize during this session that it all sounds very familiar to you. After all, who has never had doubts?

But questioning your competence again and again no matter how successful you are, waiting in angst for the fateful day when everyone will finally see how much of a fraud you are… this is the infamous impostor experience that an estimated 70% of people go through at some point in their lives.

So you’re not alone, you do belong here and I’m going to give you all the tips you need to prove it to yourself too!</dd>
</dl>

[Slides](https://github.com/Mupsi/conferences/raw/947c55ff0ce64cb6973cd0c7d4e7f760b0fa7f74/%5BSymfonyCon%202022%5D%20Fighting%20Impostor%20Syndrome:%20A%20Practical%20Handbook.pdf)  
~~Video~~

By [Marine Gandy](https://connect.symfony.com/profile/mupsi)  
![github](icon/github.png) [@Mupsi](https://github.com/Mupsi)  
![twitter](icon/twitter.png) [@mupsigraphy](https://twitter.com/mupsigraphy)

---

## Jeopardy!

<dl>
  <dt>Description</dt>
  <dd>Come and take part in the Jeopardy contest! Test your Symfony knowledge with other participants and have loads of fun! Each session features 25 questions in 5 categories about our favourite framework and its ecosystem. Sounds interesting? See you there!</dd>
</dl>

~~Video~~

By [Tomasz Kowalczyk](https://connect.symfony.com/profile/thunderer)  
![github](icon/github.png) [@thunderer](https://github.com/thunderer)  
![twitter](icon/twitter.png) [@tmmx](https://twitter.com/tmmx)

---

## Climate change and IT, scaling sustainably

<dl>
  <dt>Description</dt>
  <dd>This session will provide an overview of climate change, explore how to quantitatively reduce your carbon footprint in the cloud, and explore what actionable information is needed by the client. The ICT sector contributes ~4% of global greenhouse gas emissions – this is more than global aviation.</dd>
</dl>

[Slides](https://archive.org/download/sfcon2022_climate-change-and-the-cloud_fred-leah/2022.11.18.BATCon.Climate.change.and.the.cloud.Fred.Leah.pdf)  
~~Video~~

By [Frederic Plais](https://connect.symfony.com/profile/fredplatformsh)  
![github](icon/github.png) [@fredplais](https://github.com/fredplais)  
![twitter](icon/twitter.png) [@fredplais](https://twitter.com/fredplais)

And [Leah Goldfarb](https://connect.symfony.com/profile/leah)  
![twitter](icon/twitter.png) [@leahgoldfarb](https://twitter.com/leahgoldfarb)

---

## Calculating what we can’t see: carbon emissions in the cloud

<dl>
  <dt>Description</dt>
  <dd>The importance of full carbon emissions accounting, including virtual assets, has become the norm and is set to be an environmental compliance issue going forward. These changes are superimposed on a changing regulatory landscape (e.g. the EU’s Green Deal). Although universal common standards are sometimes lacking, our technical understanding is improving. In the interest of Building Anything Together, we will unpack Platform.sh’s approach to carbon calculations, including how we seek to allocate carbon emissions across our product profile and how our customers can contribute to minimizing their carbon footprint in the cloud.</dd>
</dl>

[Slides](https://archive.org/download/sfcon2022batcon.-calculating.what.we.can.t.see.-.-carbon.-emissions.in.the.-cloud/2022.11.18.BATCon.Calculating.what.we.can.t.see.-.Carbon.Emissions.in.the.Cloud.pdf)  
~~Video~~

By [Mary Thomas](https://connect.symfony.com/profile/marythomas)  
![github](icon/github.png) [@makermary](https://github.com/makermary)  

And [Leah Goldfarb](https://connect.symfony.com/profile/leah)  
![twitter](icon/twitter.png) [@leahgoldfarb](https://twitter.com/leahgoldfarb)

---

## Mutating a symfony project

<dl>
  <dt>Description</dt>
  <dd>Mutation Testing is a powerful technique to evaluate the quality of our tests but it's not widespread. In this talk, we will introduce Mutation Testing, compare it with code coverage and see how we can make it work inside a Symfony project using Infection.</dd>
</dl>

[Slides](https://www.canva.com/design/DAFQDOnAsCQ/crRQ3QLLwaurnjKGCp06TA/view)  
~~Video~~  
[Demo](https://github.com/isamadrid90/mutation-testing-symfony-demo/pulls?q=is%3Apr+sort%3Aupdated-desc+)

By [Isabel Garrido Cardenas](https://connect.symfony.com/profile/igcardenas1990)  
![github](icon/github.png) [@isamadrid90](https://github.com/isamadrid90)  
![twitter](icon/twitter.png) [@isabeliita90](https://twitter.com/isabeliita90)  
![mastodon](icon/mastodon.png) [@isabeliita90@mas.to](https://mas.to/@isabeliita90)

---

## Decoupling an application with Symfony Messenger

<dl>
  <dt>Description</dt>
  <dd>Quick response times are crucial. Time consuming tasks triggered in web requests should be executed asynchronously, if at all possible. In this talk I will give a short overview of what message queues are and then show a case study how we split up an application into smaller services and how we use message queues to coordinate the services.</dd>
</dl>

[Slides](https://davidbu.ch/slides/2022-11-18-symfonycon-messenger.html)  
~~Video~~

By [David Buchmann](https://connect.symfony.com/profile/dbu)  
![github](icon/github.png) [@dbu](https://github.com/dbu)  
![twitter](icon/twitter.png) [@dbu](https://twitter.com/dbu)

---

## How to handle content editing in Symfony

<dl>
  <dt>Description</dt>
  <dd>Content editing is the process of letting users create rich content directly from your project. It goes from allowing users to write simple text comments to letting users write rich documents collaboratively in real-time. Due to the inherent risks of displaying user content on your platform, it is a difficult problem to tackle in a secure, scalable and feature-rich way.

Let's discuss how the HtmlSanitizer component, Symfony UX and Mercure can be used together to build amazing editing experiences for your users.</dd>
</dl>

[Slides](https://speakerdeck.com/tgalopin/content-editing-in-symfony)  
~~Video~~

By [Titouan Galopin](https://connect.symfony.com/profile/tgalopin)  
![github](icon/github.png) [@tgalopin](https://github.com/tgalopin)  
![twitter](icon/twitter.png) [@titouangalopin](https://twitter.com/titouangalopin)

---

## What is FleetOps and why you should care?

<dl>
  <dt>Description</dt>
  <dd>As the world gets more complicated so does managing all the digital assets of an organization. Standardizing is no longer about the software, the infrastructure provider or even the location but rather the ability to manage across multi-stack, multi-location and multi-providers in a streamlined fashion. Learn about the best way to speed up your time to market across your entire organization by standardizing on next generation DevOps we call FleetOps.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Jessica Orozco](https://connect.symfony.com/profile/jessoro)  

---

## Advanced Test Driven Development

<dl>
  <dt>Description</dt>
  <dd>If you love TDD and want to improve in this programming discipline, you're in the right place. Attend this talk, and you'll learn about:

- What TDD really is
- Techniques for making your test suite more reliable
- What does getting stuck mean, and how to get out of it
- Why mocking is more about collaboration
- Acceptance tests and more!</dd>
</dl>

~~Slides~~  
~~Video~~

By [Diego Aguiar](https://connect.symfony.com/profile/mollokhan)  
![github](icon/github.png) [@MolloKhan](https://github.com/MolloKhan)  
![twitter](icon/twitter.png) [@MolloKhan](https://twitter.com/MolloKhan)

---

## A web for anyone, anywhere, anytime

<dl>
  <dt>Description</dt>
  <dd>The web is designed to be accessible by default, but we developers made a mess of it along the way. We exclude a large group of people while the web is such an intrinsic part of our daily lives nowadays.

In this talk, Rowdy will go over common mistakes and show solutions to improve your website for persons with disabilities. He will also discuss practical examples to make websites more enjoyable and usable for every user, based on their current situation.</dd>
</dl>

[Slides](https://rowdy.codes/talks/assets/pdf/20221118-symfonycon-disneyland-paris.pdf)  
~~Video~~

By [Rowdy Rabouw](https://connect.symfony.com/profile/rowdy)  
![github](icon/github.png) [@rowdyrabouw](https://github.com/rowdyrabouw)  
![twitter](icon/twitter.png) [@rowdyrabouw](https://twitter.com/rowdyrabouw)

---

## Bring your own knowledge: The Shopware App System and platform.sh

<dl>
  <dt>Description</dt>
  <dd>Getting into new ecosystems often is a huge investment of time and effort. In this talk, Niklas will show you an exception to the rule.

The exception consists of three things: A MIT-licensed, open-source e-commerce software called Shopware, the service platform.sh, and whatever programming knowledge you already have.

You will learn how to use your existing knowledge to create standalone services that hook into Shopware Shops with minimal effort from your site.

See what is possible, what you can do with the technology, where platform.sh fits the picture, and learn why it is worth trying the whole thing out.</dd>
</dl>

[Slides](https://archive.org/download/sfcon-2022-ndzoesch_symfonycon_Shopware_apps/ndzoesch_symfonycon_Shopware_apps_2022.pdf)  
~~Video~~

By [Niklas Dzösch](https://connect.symfony.com/profile/ndzoesch)  
![github](icon/github.png) [@ndzoesch](https://github.com/ndzoesch)  
![twitter](icon/twitter.png) [@ndzoesch](https://twitter.com/ndzoesch)

---

## How to Instantly Upgrade your Legacy Symfony in Minutes

<dl>
  <dt>Description</dt>
  <dd>Legacy code is side effect of any successful company. The longer your grow, the older your code is.

How can we deal with it? Rewrite? Gradual refactoring? Hire external developer team with legacy skills?

In 2022 there are tools that can handle like composer updates your dependencies. Any company or developer can refactor their huge legacy code in a couple of weeks. Bump PHP 5.3 to PHP 8.1? From PHPUnit 4 to 10 or Symfony 2.8 to 6.1?

You don't have to know a thing about the BC breaks and how-to-chagen it.
I will show you, how you can become master of change with simple command line.</dd>
</dl>

[Slides](https://slides.com/tomasvotruba/minute-symfonycon-2022)  
~~Video~~  
[Code](https://github.com/TomasVotruba/symfony-upgrade-demo-2022)

By [Tomas Votruba](https://connect.symfony.com/profile/tomas_votruba)  
![github](icon/github.png) [@TomasVotruba](https://github.com/TomasVotruba)  
![twitter](icon/twitter.png) [@VotrubaT](https://twitter.com/VotrubaT)

---

## From a legacy Monolith to a Symfony Service Oriented Architecture with zero downtime

<dl>
  <dt>Description</dt>
  <dd>Let's say you have a 15-year-old e-commerce site and you need to modernize it. You've probably heard of something like SOA or microservices and want to implement them. But you have no idea how to move from a monolith to SOA while maintaining live production the whole time.

In this talk, we'll walk you through how we approached this, what's the first step? How we leveraged the Strangler Fig Pattern (presented in Shawna Spoor's talk) with Symfony to set up our migration path. How to manage such an architecture on a daily basis? How do manage source code? How do we handle users's session between legacy and new apps? How do we benefit from Symfony's Container in the legacy part? How to hunt for bugs thanks to OpenTelemetry?

This talk will give you some tips from our experience.</dd>
</dl>

[Slides](https://slides.com/skigun/from-monolith-to-soa-with-zero-downtime)  
~~Video~~

By [Clément Bertillon](https://connect.symfony.com/profile/skigun)  
![github](icon/github.png) [@skigun](https://github.com/skigun)  
![twitter](icon/twitter.png) [@BERTILLONClment](https://twitter.com/BERTILLONClment)

---

## Headless possibilities

<dl>
  <dt>Description</dt>
  <dd>Headless is a term emerged recently in the web industry. It was coined to describe a backend system that provides core features but doesn't provide delivery, just a REST API interface. Countless products like CMSes and eCommerce systems state being headless or at least having a headless mode. Is it something completely new or just good old "divide et impera"? In this presentation, we will explore the headless buzz, how it is related to decoupled architecture and API driven development, it's pros and cons. Also, what about the head?</dd>
</dl>

[Slides](https://www.slideshare.net/secret/AXYH9mdmsIkQn3)  
~~Video~~

By [Ivo Lukač](https://connect.symfony.com/profile/gof)  
![github](icon/github.png) [@ilukac](https://github.com/ilukac)  
![twitter](icon/twitter.png) [@ilukac](https://twitter.com/ilukac)

---

## Modernizing with Symfony

<dl>
  <dt>Description</dt>
  <dd>A legacy application. It still earns the money, but maintaining the old code base is getting harder and harder. Feature development is too slow and the bug tracker is full of severe defect reports.

Rewriting the whole application is something your developers would simply love to do. But the rewrite probably won't go live before it's running out of budget.

Let's have a look at simple techniques that allow us to transform our legacy application step by step into a modern Symfony application.</dd>
</dl>

~~Slides~~  
~~Video~~

By [Alexander M. Turek](https://connect.symfony.com/profile/derrabus)  
![github](icon/github.png) [@derrabus](https://github.com/derrabus)  
![twitter](icon/twitter.png) [@derrabus](https://twitter.com/derrabus)  
![mastodon](icon/mastodon.png) [@derrabus@phpc.social](https://phpc.social/@derrabus)

---

## Painless authentication with Access Tokens

<dl>
  <dt>Description</dt>
  <dd>Via some simple but real scenarios, we will discover the power of the new AccessToken Authenticator shipped in Symfony 6.2. For example, we are developing a SaaS product, which exposes a private API. Our users can register many applications into their accounts, for each one we will generate an API Token that users must inject in their requests. Now, with a pinch of YAML and a dash of PHP, we will be able to authenticate users from their API Token. In this talk, I will show you how it also works with JWT and some other exotic tokens!</dd>
</dl>

[Slides](https://welcomattic.github.io/painless-authentication-with-access-token)  
~~Video~~

By [Mathieu Santostefano](https://connect.symfony.com/profile/welcomattic)  
![github](icon/github.png) [@welcoMattic](https://github.com/welcoMattic)  
![twitter](icon/twitter.png) [@welcoMattic](https://twitter.com/welcoMattic)  
![mastodon](icon/mastodon.png) [@welcomattic@phpc.social](https://phpc.social/@welcomattic)

---

## Dynamic Validation with Symfony

<dl>
  <dt>Description</dt>
  <dd>It might happen on some of your API's endpoints, that the object your app is waiting for depends on the data sent. Say, the user sends `{type:foobar, data: XXX}`, then the `XXX` formats will depend on the type `foobar`.

So how can one validate this data if we don't even know its type ?
Well come on in, I'll show you how ! You can actually validate dynamic data by using the most of the features available in Symfony.</dd>
</dl>

[Slides](https://speakerdeck.com/marionleherisson/how-to-dynamically-validate-data-with-symfony)  
~~Video~~  
[Code](https://github.com/MarionLeHerisson/validation)

By [Marion Hurteau](https://connect.symfony.com/profile/marionleherisson)  
![github](icon/github.png) [@MarionLeHerisson](https://github.com/MarionLeHerisson)  
![twitter](icon/twitter.png) [@MarionHerisson](https://twitter.com/MarionHerisson)

---

## The Evolution of Symfony: Now and to the Future!

<dl>
  <dt>Description</dt>
  <dd>With the release of 6.2, Symfony will contain somewhere near *500* new features from just the past 12 months! Wow!

And, while many of these are small, the landscape of *how* Symfony apps are developed continues to evolve. In this talk, we'll look at some of the most important changes, from new dependency injection attributes, framework-extra bundle features in Symfony, Symfony UX, testing, and more! Basically... a quick catch-up on 12 months, *thousands* of commits, and hundreds of releases across numerous repositories. Let's go!</dd>
</dl>

[Slides](https://speakerdeck.com/weaverryan/the-evolution-of-symfony-now-and-to-the-future)  
~~Video~~

By [Ryan Weaver](https://connect.symfony.com/profile/weaverryan)  
![github](icon/github.png) [@weaverryan](https://github.com/weaverryan)  
![twitter](icon/twitter.png) [@weaverryan](https://twitter.com/weaverryan)
