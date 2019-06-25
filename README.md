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
1.  Install Cursive
2.  Open project (should recognise as clojure deps)
3a. <F4> to open module settings
3b. Open SDK and select 12.0.1
4.  Select Run -> Edit Configurations -> + -> Clojure Repl -> Local
4a. Name: ClojureScript REPL
4b. nREPL
4c. Run with Deps
4d. Before launch, add Build
5. Run ClojureScript REPL and select cljs from drop down
6. Go to core.cljs and load NS


