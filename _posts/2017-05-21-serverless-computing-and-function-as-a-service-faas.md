---
layout: post
title: "Serverless Computing and Function as a Service (FaaS)"
description: "Serverless Computing and Function as a Service (FaaS)"
date: 2017-05-21
tags: [serverless, computing, faas]
comments: true
share: true
---

Everybody in development community is talking about serverless computing these days and how quickly they
can migrate their products and services to this new architecture. Here will try to break a little ice on the topic.

> Serverless is becoming the face of new technical revolution backed by container technology

### Can we really deploy applications “serverless” ?
No, Serverless is just another _marketing buzzword_ which has gained too much traction.
More accurate word for serverless computing would be __Function as a Service__ or __FaaS__. In serverless computing majority of the
server side book-keeping is automatically handeled by 3rd party service and developers just focus on write application logic
in one of the vendor supported languags and call it a _functions_.
Each function is automatically exposed via API ready to be consumed by other services/ functions as soon as the funtions is deployed.
Infrastructure provisioning to run functions and auto-scaling is also offered by 3rd party providers.

Serverless offerings from AWS Lambda, Google Compute Engine, Miscrsoft Azure
have made it tremendously easy for developers to deploy their traditional apps in a serverless fashion.

### Advantages and why should anyone care ?

Whether you’re building a chat app or the next Pokémon GO, there are plenty of reasons to go serverless:

1. Decreased time to market. Serverless approaches allow developers to create new apps in hours and days instead of weeks and months. Examples abound in new apps that rely on third-party APIs for services like: authentication (OAuth), social (Twitter), maps (Mapbox), artificial intelligence (IBM’s Watson), and more.

2. Enhanced scalability. Everyone wants his app to be the next Facebook, but if that happens, can it handle the load? Provisioning infrastructure just in case is a big risk — but so is being unprepared when success strikes. Serverless architecture means you don’t need to make that choice. One online training program scaled to 40,000 users in six months without a single server.

3. Lower cost. In terms of both computing power and human resources, serverless saves. Why pay to reinvent the wheel for authorization, presence detection, and image processing? Or to manage infrastructure? And if there’s no need for always-on servers, operational costs plummet. The days of spending hundreds of thousands of dollars for servers are gone.

4. More time for user experience. Users don’t care about infrastructure; they care about features and their experience. Serverless architecture allows teams to focus resources on the elements that keep users happy. The Climate Corporation, for example, uses serverless infrastructure to give growers a rich interface to a real-time view of farm equipment operations, informing their decisions and enhancing operations.

5. Improved latency and geolocation. An app’s ability to scale depends on three things: its number of users, those users’ locations, and network latency. Today’s apps have global audiences, which can create latencies that diminish experiences. With serverless, providers have points of presence near every user, and apps perform equally well for everyone. For example, Gett provides on-demand delivery services worldwide, so it chose serverless for its low-latency, real-time messaging.
From photo-sharing apps to farm data dashboards to connected jet engines, serverless can accommodate the wide-ranging needs of app developers.
As data loads continue to grow, expect to see serverless become a standard approach to offloading functions to execute closer to end users and devices. By reducing costs, latency, time to market, and complexity, the serverless model is poised to become a staple of the app space.

Go serverless …

