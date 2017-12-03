### December 2

Formally wrote up my dedication to Devember, and created this repository. 

### December 1

I wrote a python script to add New Relic hosts to each alerting condition they should be a part of in a given policy. It could still use some polish around usability, but the hard parts are done, and it's functional. Afterward, I decided to try reimplementing it in Go, since I'm trying to improve proficiency in both languages. 

Python's requests library is super nice, and handling the JSON returned by the New Relic API was smooth as butter. Attempting to do the same thing in Go is neither as quick nor as painless with the way the http library is set up, as well as having to unmarshal the JSON into a struct to use it.
