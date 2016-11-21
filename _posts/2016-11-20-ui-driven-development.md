---
layout: post
title: UI Driven Development
author: Michael Gattuso
---

Historically I have been a big fan of Domain Driven Development. When I start a problem I usually think about it in terms of the domain model and the associated database tables and columns. Sure, this model will evolve through the project but historically I feel that I really “get” the project once I have got two solid arms around the domain model.

When I work with [angular.js](https://angularjs.org/) I have noticed that I am a lot more interested in getting the UI layer down first and then worrying about persisting the data. In fact I am more likely to start stuffing data into local storage in the browser while I figure out the UI until I am happy with the shape of data needed to support the user experience. This process of UI > Local Storage > Persisted Storage feels faster and I think it is.

## Late to the Party?

Having not really though about this approach as a discipline In coming up with a title I thought about "UDD" or "UI Driven Development". I dropped the term into Google to see what else was out there on the topic. Turns out (of course) that I am way late to the party and one my favorite bloggers has addressed this very topic a [very long time ago](https://blog.codinghorror.com/ui-first-software-development/).

From the post:

> Of course, UI is hard, far harder than coding for developers. It's tempting to skip the tough part and do what comes naturally -- start banging away in a code window with no real thought given to how the user will interact with the features you're building.

> Remember, to the end user, the interface is the application. Doesn't it make sense to think about that before firing up the compiler?

## Deferred Execution

For me a tool like angular provides this opportunity to get the application in front of the customer as early as possible and then I can start working on the server side stack to support the thing.