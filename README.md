# TicketSwap assessment
Oops! You and your team were asked to implement a new marketplace system for selling and buying tickets. Your colleague already started working on a proof of concept, but had to leave before finishing it! 
Now it is up to you to finish what was started.

The business rules are as follows:
- A listing contains multiple tickets. 
- Tickets can contain multiple barcodes.
- Sellers can create listings with tickets.
- Buyers can buy invididual tickets from a listing.
- Once all tickets have been sold for a listing, it is no longer for sale.
- It should not be possible to create a listing with duplicate barcodes in it.
- It should not be possible to create a listing with duplicate barcodes within another listing.
- Though, it should be possible for the last buyer of a ticket, to create a listing with that ticket (based on barcode).

There are some concrete classes for implementation and there are some unit tests. Your job is to:
- make sure all the business logic above is implemented and test
  - make sure all the tests pass
  - there are skipped tests, you need to implement the missing functionality
- **bonus** we know some sellers have nefarious plans and try to scam buyers. To prevent that, we want to only sell listings that have been verified by an admin. Make the implementation and the accompanying unit tests for this.

Because your colleague suddenly left, not everything that is already there might be so nice, or even conform to the business rules. You are free, encouraged even, to rewrite those parts in the implementation, tests or overal design that you think are in need of it. You are also free to add any library that you think you need. We do however ask that you don't use a database to make the business rules work.

 If you have any questions you can always [contact us][contact].

## Setup
First of all, it is assumed that you can run PHP (7.2+) and composer locally.

### Download repository
You can download/clone the repo to your local machine and follow the next instructions to get everything up and running.

### Installing dependencies
```
composer install
```

### Start unit tests
```
vendor/bin/phpunit tests
```

## Handing in the assessment
When you're finished developing the application you can send it to us in reply of the mail you got with this assessment.

## Good luck
And again if you have any questions, [let us know][contact]!

[contact]: mailto:pascal@ticketswap.com

