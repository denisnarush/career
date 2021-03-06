# Career


### Career Road Map
- [x] Junior Sofware Engineer
- [x] Sofware Engineer
- [x] Senior Software Engineer
- [ ] Development Leader

### Primary Skill
- [x] Framework (Implement Web App)
  - [x] Bootstrapping application
  - [x] Framework specific patterns
  - [x] Code conventions
  - [x] Managing modules/dependencies
  - [x] Framework performance nuances
    - [x] AOT, Lazy Loading, Pure Pipes, Resolve Guard, Unsubscribe from Observables
  - [x] Framework security features
    - [x] [https://angular.io/guide/security](https://angular.io/guide/security)
  - [x] i18n, l10n
    - [x] [https://v8.angular.io/guide/i18n](https://v8.angular.io/guide/i18n)
  - [x] e2e testing
    - [x] [https://v8.angular.io/guide/testing](https://v8.angular.io/guide/testing)
  - [x] Advanced framework features, e.g. Reconciliation algorithm and Fiber architecture for React or AOT and Zone.js for Angular (just an example)
    - [X] AOT [https://v8.angular.io/guide/aot-compiler](https://v8.angular.io/guide/aot-compiler)

       ```
       // Faster rendering,
       // Fewer asynchronous requests (html, css),
       // Smaller Angular framework download size,
       // Detect template errors earlier,
       // Better security.
       ```
    - [x] Zone.js
  - [x] Discuss framework history (1-2 prev versions + possibly upcoming features)

- [x] Multitasking
  - [x] JS event loop
      
     ![Schema](https://habrastorage.org/webt/l0/z9/q2/l0z9q2s-zdltplomxlim269pu7k.png)
     
     [![Jake Archibald: In The Loop - JSConf.Asia
](https://img.youtube.com/vi/cCOL7MC4Pl0/maxresdefault.jpg)](https://www.youtube.com/watch?v=cCOL7MC4Pl0)

  - [x] Promises
    - [x] [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)

      ```javascript
      new Promise(function(resolve, reject) {
        // resolve(результат) при успешном выполнении
        // reject(ошибка) при ошибке
      })
      // onFulfilled сработает при успешном выполнении
      .then(onFulfilled)
      // onRejected сработает при ошибке
      .catch(onRejected)
      ```
  - [x] Async/await
    - [x] [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function)
    - [x] [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/await](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/await)
  - [x] Spread "[...](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax)" operator
  - [x] Iterators/Generators
    - [x] [https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Iterators_and_Generators](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Iterators_and_Generators)
  - [x] [Web workers](https://developer.mozilla.org/en-US/docs/Web/API/Web_Workers_API)
  - [x] [Service workers](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)
  - [x] RxJS core concepts (if specified): Observable, Observer

    ```javascript
    const apps$ = new Observable(subscriber => {
      subscriber.next(1)
    });
    // An Observer is a consumer of values delivered by an Observable.
    // Observers are simply a set of callbacks, one for each type of notification
    // delivered by the Observable: next, error, and complete.
    // The following is an example of a typical Observer object:
    const observer = {
      next: x => console.log('Observer got a next value: ' + x),
      error: err => console.error('Observer got an error: ' + err),
      complete: () => console.log('Observer got a complete notification'),
    };
    // To use the Observer, provide it to the subscribe of an Observable:
    apps$.subscribe(observer);
    ```
  - [x] RxJS core concepts (if specified): Operators - most common ones (filer, findIndex, delay, tap, map, pluck, switchMap, reduce)
  - [x] RxJS core concepts (if specified): Subjects
  
    ```javascript
    // A Subject is like an Observable, but can multicast to many Observers.
    // Subjects are like EventEmitters: they maintain a registry of many listeners.
    subject.subscribe({
      next: (v) => console.log(`observerA: ${v}`)
    });
    subject.subscribe({
      next: (v) => console.log(`observerB: ${v}`)
    });
    
    new BehaviorSubject(0); // 0 is the initial value
    new ReplaySubject(3); // buffer 3 values for new subscribers
    ```
  - [x] RxJS core concepts (if specified): Cold vs hot observables

    ```javascript
    // When the data is produced by the Observable itself, we call it a cold Observable.
    // When the data is produced outside the Observable, we call it a hot Observable.
    ```
  - [x] RxJS core concepts (if specified): Typical applications

- [x] Design & Architecture (Patterns or Principles)
  - [x] GOF patterns. Can explain, identify, use
    - [x] The book was written by 4 authours: Erich Gamma, Richard Helm, Ralph Johnson, John Vlissides
    - [x] [Patterns](https://refactoring.guru/ru/design-patterns)
      - [x] Creation: [Singletone](https://refactoring.guru/design-patterns/singleton),
      - [x] Structural: [Facade](https://refactoring.guru/ru/design-patterns/facade), [Wrapper/decorator](https://refactoring.guru/ru/design-patterns/decorator)
      - [x] Behavioral: [Observer](https://refactoring.guru/design-patterns/observer),
  - [x] [SOLID](https://samueleresca.net/solid-principles-using-typescript/)/[Inversion of control/DI](https://khalilstemmler.com/articles/tutorials/dependency-injection-inversion-explained)
    - [x] DI [https://v8.angular.io/guide/dependency-injection](https://v8.angular.io/guide/dependency-injection)
  - [x] Anti-patterns [article](https://habr.com/ru/post/59005/)
  - [x] Static typing: [soundness and completeness](https://eschew.wordpress.com/2009/08/31/sound-and-complete/)
    - [x] related to TypeScript [soundness](https://www.typescriptlang.org/docs/handbook/type-compatibility.html#a-note-on-soundness)
  
  
 ### Results SE > SSE
 - [x] English level: B1-B1+ (B1)
 - [x] Years: B (A+)
 - [-] Primary Skill: Qualified (Qualified)
 - [x] Responsibilities: Correspond (Correspond) ?
 - [x] Analytical thinking / Problem Solving: B (A)
 - [x] Communication / Interaction Skills: B (A)
 - [x] Stress Tolerance: B (A+)
 - [x] Accountability / Initiative: A (A)
 - [x] Customer Focus: B (A)
 - [x] Teamwork / Collaboration: B (A)
 - [x] Learning capability: B (A)
 - [x] Self-Management: B (A)
 
# Self-Presentation ([responsibilities](https://confluence.exadel.com/pages/viewpage.action?pageId=76121144))
## Narush Denis

- I ❤ vanilla JS
- HTML, CSS Ninja
- Know about Flow and I believe that the development is a creative process
- Have more than 10 years of commercial experience
- Have 3 years of mentoring experience. All students successfully found jobs in IT-companies
- Researching of animations and visual effects what can blow the mind from CSS3 to WebGL2

### Stack
- HTML/CSS (sass)
- Javascript (typescript)
- Angular, Ionic (base on angular)
- Jest
- Jenkins (build configuration)

Full list can be found on my [github](https://github.com/denisnarush/MY) page.

### Projects (at Exadel)
#### Verifone (current)
Multi app project were each app defines each own role from app development to end user usage in term of bank system with cooperation of unique Verifone's terminals. One applactions was developed for Web and Mobile (Android) platforms.
- `Angular 8, Ionic, Akita, Bulma, Jest, NX`
#### GHX
Web and mobile interface that brings the user experience of a consumer webshop together with powerful workflow and approval processes. GHX helps hospitals and healthcare suppliers to increase efficiency, lower costs and provide better patient care.
- `Angular, Ionic, Material, Jasmine`
#### WK eReader
The WK eReader brings the trusted and authoritative legal, business, and tax analysis from Wolters Kluwer Law & Business directly to your iPad or Android devices. This application gives you instant linking to relevant cases, statutes and regulations, as well as enhanced functionality for efficient research work flow and increased productivity.
- `AngularJS, Cordova, Sencha Touch, Protractor`


## Responsibilities
Current project gave me possibility to consolidate skills that are required to senior developer position.

#### Customer
I would say that escalate issues in my own area is a typical part of your daily work. As a results - taking part in technical descussions, clarifications and analyzation requirements is a regular situation. It gives me an understanding of business processes, domain. You become independent, self-reliant and self-manager - "If you need something: go and take it". And at the end of each sprint, milestone, we put on demonstrations for product owners.
#### Project Management
The project has 2 week sprints at the beginning of each sprint, there is sprint planning and grooming. After each grooming session, the task evaluation process is started there i estimate my own stories and provide help with estimation for Nastassia. In a previous project, I help my teammates adapt to the BEM methodology, which I integrated into the styling process.
#### Team
On current project I helped Nastassia with onboarding and also I provided help for other developers were are start work on submodules.
#### Quality
One part of my work on previous project was created style guide for styling components using BEM methodology. Performs code review and analysis requirements for own area is a daily routine. Same to the quality of my technical solutions - working on code enhancement on free time.
#### Area of Expertise (Development)
It's a little funny, but I define the task by the time it takes to complete, instead of setting the difficulty level. So I don’t remember the task I couldn’t complete. I am often asked to help find a bug or help with html/css (sometimes floating elements are a pain in...). Most of my experience is with hybrid mobile app development. One of the interesting tasks was the easter egg in our Ionic app.
#### Expertise
Basically all my free time I devote to video tutorials or small, not obvious thoughts about the code. And I love to share these thoughts with my teammates (especially Andrey). I even set up a Skype group chat in the Grodno office to discuss some solutions or interesting topics I found. The last such topic was about 16bit JS. I was involved in the technical interview and was a mentor for junior employee in the local office. Often I take part in R&D projects.


## Feedbacks
-----
> For the past year (almost) I have had the pleasure of working with Denis Narush on my team.
> 
> I could not have asked for a better team member than this:
> - Extensive knowledge of Angular, IONIC and WEB in development .
> - A great team member who can be trusted.
> - Also available outside of work hours for help and advice.
> - Always fulfils all his duties successfully and on time.
> 
> In fact he often served as my replacement when I was absent, both from the staff and from the management.
> 
> As part of his work on the Marketplace project, Denis led and developed the following majors areas:
> - Follow the entire IONIC application, including build and configure all relevant scripts
> - The entire TAGS area in the Marketplace system, both on the merchant side and the manager side.       
> - The process of creating the bundles, and manage them.
> 
> In addition to all this Denis helped and was Nastasia's mentor in the process of her admission to the team, and all the Dashboards section that she developed.
>
> And not just working with our team - Denis has helped me quite a bit to support other teams in the company who are participating in the project.
> 
> Some of the infrastructure we wrote on the team is used by all of Verifon's new infrastructures.
#
<div align="right">[@Roee Ovadia](https://github.com/roeeovadia), team leader of Verifone project.</div>

-----
> For the past year I have been studying Frontend developement with Denis Narush as mentor.
> 
> From the first steps it was clear that he has very strong and wide knowledge in tech stack based on HTML, CSS, JS from native features to modern frameworks and addons.
> 
> Also he has well structured approach to teaching from basics to complex things.
> 
> Thankfully to him I got motivation and big interest not only in Frontend but in programming in general.
> 
> I could ask him for professional advice or code review almost any time.
> 
> It was very helpful and positive experience of working with Denis.
> 
> I hope we 'll continue professional and informal communication in future.
#
<div align="right">[@AlexanderBazukevich](https://github.com/AlexanderBazukevich), learner.</div>

 
 # Notes
 - Start day: 2/09/2020. Day when my personal HR tell me that she add me to the list for the English interview.
 - Date 9/09/2020: spent [*1h*] for understanding all requirements and phases for the interview.
 - Date 11/09/2020: spent [*1.5h*] for preparing to English + interview.
 - Grabing feedback from TL Roee.
 - Grabing feedback from Learner Alex.
 - Date 21/09/2020: recived feedback from English interview.
 - Start working on "self-presentation".
 - Date 30/09/2020: "self-presentation" complete & submited.
 - Date 09/10/2020: Technical interview was skipped. One person was sick.
