# Daily Inspo App

Create an application that will send you a daily text with an inspirational message or image (*some* might suggest cute animals, like kittens).

You will use Twillio's API to handle sending text messages from your Rails application.


## Get Started
1. Create a new rails app in this directory using the following command:
```
$ rails new .
```

1. Sign up for a Twillio account: https://www.twilio.com/

1. Keep the Twilio Docs handy in a new tab: https://www.twilio.com/docs/

1. Review their quickstart guide for sending SMS and MMS for Ruby Development: https://www.twilio.com/docs/quickstart/ruby/sms

1. Look at other online resources that utilize Twilio's texting feature into a rails application. Here are a few to get you started:
  - https://www.twilio.com/blog/2016/04/receive-and-reply-to-sms-in-rails.html
  - https://www.twilio.com/blog/2014/10/twilio-on-rails-part-2-rails-4-app-sending-sms-mms.html
  - https://www.sitepoint.com/adding-sms-capabilities-to-your-rails-app/
1. Build the application with guidelines listed below

1. When finished, deploy to Heroku

## Guidelines
**Wave 1:** Send a text from a local rails application
  - Add the Twilio gem
  - Store your Twilio API Token and SID with the Figaro Gem
  - Setup a message controller and model so that you can enter a number, through an html form, and immediately have a text sent to your phone.

**Wave 2:** Have texts sent daily
This part gets tricky!
- Spend about 30 minutes researching various ways you can schedule tasks to run automatically, with an application hosted on heroku
- Spend another 30 minutes - 1 hour trying to implement one of those strategies. Remember to branch, just in case it doesn't work!
- If you are feeling like the strategy you implemented isn't working, try [this out](https://devcenter.heroku.com/articles/scheduler)



### Optional Enhancements
- Use Giphy's API to generate a random gif, based on a specific search term, to send instead. 
