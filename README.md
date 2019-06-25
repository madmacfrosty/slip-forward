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

# initial setup

Created deps.edn and core.cljs from scratch as per Clojurescript quick start

For intelliJ:
-  Install Cursive
-  Open project (should recognise as clojure deps)
-- <F4> to open module settings
-- Open SDK and select 12.0.1
-  Select Run -> Edit Configurations -> + -> Clojure Repl -> Local
-- Name: ClojureScript REPL
-- nREPL
-- Run with Deps
-- Before launch, add Build
- Run ClojureScript REPL and select cljs from drop down
- Go to core.cljs and load NS

# Node setup
- brew install npm
- npm install source-map-support
- clj -m cljs.main --target node --optimizations simple --output-to main.js -c slip-forward.core

This produces a main.js that is ready to load we think

