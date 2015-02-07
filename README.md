# kalinka

## Update

This is a quick port of the original kalinka demo.
Note that it still uses a (now) very old jQuery and version of Any+Time.
Maybe it will get an update one day?

## About

kalinka: Google Calendar Link-maker and Any+Time jQuery demo

Any+Time was one of the more interesting options I covered in my
[Quick Review of jQuery Date/Time Widgets](http://tardate.blogspot.com/2010/06/quick-survey-of-jquery-datetime-widgets.html).

Any+Time had a lot more functionality than I got to investigate at the time, and there were some specific features I wanted to checkout in more detail - in particular timezone handling - so I built another little demo called kalinka.

kalinka is a simple tool to construct Google Calendar Event URLs without needing to publish an event in your own calendar. You can then put the link in an email or a website. Other people can then use the link to create the event in their own Google Calendar.

kalinka mimics the basic functionality of the Google Calendar Event Publisher, except that it also demonstrates using Any+Time to offer specific control of the timezone.

Try out [kalinka here](http://kalinka.tardate.com), and feel free to pillage the scripts.


## Sinatra Web App

A sinatra web app is included in this repo for the purpose of hosting at [kalinka.tardate.com](http://kalinka.tardate.com).

To run the app locally:

    $ bundle install
    $ ruby web_app.rb


## Contributing

1. Fork it ( https://github.com/tardate/kalinka/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new Pull Request
