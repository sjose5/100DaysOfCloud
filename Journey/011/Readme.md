## EC2 Pricing Models
Today I'm going to learn more about the EC2 Pricing Models. So, I learned there are 4 ways you can pay for EC2. There are On-Demand, Spot, Reserved and Dedicated.

## On-Demand 
* Is the least commitment, no upfront payment, no long-term commitment, and you are charged by the hr or min.  This is good for short-term use or unpredictable applications.

## Spot 
* AWS has unused compute capacity so they want to make money on there extra instances laying around so they give you a better price.  So, thats why it's the biggest savings but there are some trade offs.  The instance can be terminated at any time if someone needs it and offers a higher price and they wont charge you if they terminate your instance. Spot is good for applications that have start and end times or applications that are only feasable at very low costs.

## Reserved 
* Is best for long-term and is used for applications that have a steady state, predictable usage, or require reserved capacity. 
## There are 3 options in Reserved there is: 
* Standard which gives you 75% more savings then Dedicated but you cant chanage your RI.  
* Convertible gives you 54% savings compared to On-Demand and it allows you to change your RI.   
* Scheduled is when you reserve instances for a specific time.

### The terms for Reserved are 1 or 3 year contracts.  You save more if you have a longer term.

### Payment Options are Up-front, Partial Upfront or No-Upfront

## Dedicated 
* Is the most expensive and it's used when you have strict server bound licensing that won't support multi-tenancy like Enterpirses and large Organizations. Dedicated is used for single-tenant. When the customer has dedicated hardware and is physically isolated. It is offered as On-Demand or Reserved.

Social Proof
https://twitter.com/sammy5_j/status/1294302157043167232

