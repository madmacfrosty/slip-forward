# slip-forward

A gmail relay agent to automate forwarding my pay slips

# rationale

- Clojurescript over Javascript because I know Clojure
- Google functions because I think I'll spend more time on business logic once I've mastered them 

# tasks

1. Create hello world clojurescript from first principles
2. Deploy to google
3. Change function to count mails matching a filter
4. Write separate function to get attachments?

## Setup

To get an interactive development environment run:

    lein figwheel

and open your browser at [localhost:3449](http://localhost:3449/).
This will auto compile and send all changes to the browser without the
need to reload. After the compilation process is complete, you will
get a Browser Connected REPL. An easy way to try it is:

    (js/alert "Am I connected?")

and you should see an alert in the browser window.

To clean all compiled files:

    lein clean

To create a production build run:

    lein do clean, cljsbuild once min

And open your browser in `resources/public/index.html`. You will not
get live reloading, nor a REPL. 

