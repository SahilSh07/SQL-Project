# SQL-Project

### INTRODUCTION


Ron and his buddies founded Foodie-Fi and began selling monthly and annual 
subscriptions, providing clients with unrestricted on-demand access to exclusive cuisine 
videos from around the world.

This case study focuses on the use of subscription-style digital data to answer critical 
business questions about the customer journey, payments, and business performance.

#### Table PLANS Description

There are 5 customer plans:

1. Trial— Customers sign up for a 7-day free trial and will be automatically enrolled in the pro monthly subscription plan 
unless they unsubscribe, downgrade to basic, or upgrade to an annual pro plan during the trial.

2. Basic plan — Customers have limited access and can only stream their videos with the basic package, which is only 
available monthly for $9.90.

3. Pro plan — Customers on the Pro plan have no watch time limits and can download videos for offline viewing. Pro 
plans begin at $19.90 per month or $199 for a yearly subscription.

#### Table SUBSCRIPTIONS Description

  Customer subscriptions display the precise date on which their specific plan id begins.

  If a customer downgrades from a pro plan or cancels their subscription — the higher program will remain in place until 
  the period expires — the start date in the subscriptions table will reflect the date the actual plan changes.

  When clients upgrade their account from a basic plan to a pro or annual pro plan, the higher plan becomes active 
  immediately.

  When customers cancel their subscription, they will retain access until the end of their current billing cycle, but the 
  start date will be the day they opted to quit their service.
