clojure-class-hackers-and-founders
==================================

This repo contains course material for the Hackers and Founders Clojure Class, to be held June 3, 2012.

# Class Preparation

To prepare for the hackthon portion of the class, please download and install [Leiningen 1.x](https://github.com/technomancy/leiningen). Leiningen (pronounced "line" for short) is a build tool for Clojure. It's very handy for creating new Clojure projects, building, running, etc.

Please verify Lein is working by creating a new project and starting a REPL:

````bash
$ lein new myproject
$ cd myproject
$ lein repl
````
You should see a REPL come up, looking something like this:

````bash
REPL started; server listening on localhost port 55096
user=>
````

Try a little Clojure code to prove it's working. Type...
````clojure
(println "Hello Clojure!")
````
... and hit enter. You should see something like this:

````bash
user=> (println "Hello Clojure!")
Hello Clojure!
nil
user=>
````bash
