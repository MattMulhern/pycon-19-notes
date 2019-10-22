# machine learnning
- automated lang  processing bot
- ui concept: allowing false positives to be easily ignored -> bettere ux + more likely to be ued & gather data
- tighter coupling between tecchies and design necessary in ML
- S1 -> jub NB + regexes + python state machine
- S2 -> FSM + Search engine (what was the name?)
- S3 -> ec2 backend only 
- S4 -> UX -> allow stakeholders to see demo
- fed historical questions to build up knowledga base
- limitation of search engine based-> leads to false positives since it always returns something! basically ranking results, no filtering
-- switched to keyword search instead
- no conversational state manageent, simple Q&A only
- rapid prototyping!
- Q on false positive f=detction
- point on yes/no "was that right?" in ui, people dont say yes!
-- answer was to treat no response as positive(ish): hard/soft resolution.
-- possible problem with "no that want helpful" getting hit *but the ML showing the right answer*! i..e "i didn't want that answer.

# raincloud plots - pretty graphs 
- slides.com/davidepoggiali
- breakdown of grah types
- `pip install raincloud`
- seabourne dependency
- takes in pandas dataplot

#  twillo flask app
-  test number, txt 'yes' or 'no' to  +44 7403 929 354
- python3 flask
- locally running app registered with twillo.
- twillo recieves SMS and forwards to registered webook i.e. your app over HTTP
- forismatic api - getQuotes()

# pflacs
- http://qwilka.github.io

# AWS "Automate everything"
-  openSCAP - automated remediation playbooks for ansible
- ansible book -> girlyguy?
- manual type sequences to pull kickstartfile from grub config on boot
- ARX - upstream ansible role-based (upstream of ansible tower)
- `ansible-doc` : search for available modules
- molecule -> automates ansible playbook testing across platforms
- `pandoc` used for the presentation!
- cookiecuttter for molecule templates
- `yapf` - alternative to black for styling
- appsec
-- bandit
-- sonarqube
-- zap scan
-- arachni
- `cookiecutter` for app code template!
- openpracticelibrary.com
- github: crivetiamihai

# keynote - magic methods
- `nicktimko` github
- `collections.abc` abstract base classes - helper added to class definition to implemente container types e.g collections.abs.Mapping  generated __len__, __keys__ __values etc.
-- breaking changes coming in 3.8, beware!

# vacation planning
- @brendantierney
- "machine learning is a thing labeller really"

# micropython
- github.com/deanstheory (sean doherty)
-- micropython kernel notebook, wont work normally
- esp32  controllers
- online emulator possible for playtime
- LORA - LOng RAnge chip for wireless comms (low data rates)
