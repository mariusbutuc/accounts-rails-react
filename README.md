## A mock expense tracking app
For [this _React.js - A guide for Rails developers_ guide](https://www.airpair.com/reactjs/posts/reactjs-a-guide-for-rails-developers), we are building a small application from scratch to keep track of our expenses; each record will consist of a date, a title and an amount. A record will be treated as Credit if its amount is greater than zero, otherwise it will be treated as Debit.

Summarizing, the application will behave as follows:
  * When the user creates a _new record_ through the horizontal form, it will be appended to the records table
  * The user will be able to _inline-edit_ any existing record
  * Clicking on any Delete button will remove the associated _record_ from the table
  * Adding, editing or removing an existing record will _update the amount_ boxes at the top of the page
