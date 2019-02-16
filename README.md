# What is Ultralist? {#what}

Ultralist is a task management system for technical people.  It includes a command-line component that is very fast and stays out of the way.  There is also a beautiful webapp that seamlessly syncs with the command-line.

Ultralist is based off of the [Getting Things Done](https://en.wikipedia.org/wiki/Getting_Things_Done) system.  It has a concept of due dates, projects, and contexts.

# Installation {#installation}

The `ultralist` binary is free and open-source.

* On Mac OS:  `brew install ultralist`
* For other systems, you can get the binary directly from the [Ultralist Github releases page](https://github.com/ultralist/ultralist/releases).
* If you have `go` installed, you can run `go get github.com/ultralist/ultralist`.

# Overview {#overview}

Use ultralist to organize + prioritize your tasks.  It's a super-fast binary
that sits on the command-line and stays out of your way.

<script id="asciicast-226005" src="https://asciinema.org/a/226005.js" async></script>


Ultralist has **2 major components:**

* The `ultralist` command-line app, which is free and [open
source](https://github.com/ultralist/ultralist).
* The [ultralist.io](https://app.ultralist.io/login) service, which includes a webapp, phone apps (coming soon),
and seamless syncing across all devices.  

Ultralist.io is currently in a free public beta, but will be a paid service at some point.

# Ultralist concepts {#concepts}

Since Ultralist implements a version of GTD, it has similar concepts:

#### Contexts

Ultralist knows about _contexts_, which answers the question of "what do I need
in order to accomplish this?".  Contexts are denoted with an `@` symbol. 

**Examples of contexts**

* `chat with @bob`
* `@call garage about car repair`
* `@email my question about the project update`

#### Projects

_Projects_ are defined as outcomes that will require more than one action step
to complete.  So, a project may have multiple todo items.

**Examples of projects**

* `+smallTasks ping @bob about the security bulletin`
* `+mobileDev ask @george what is next on the roadmap`

#### Due dates

Due dates are critical to Ultralist, and are a first-class citizen.  This is what separates Ultralist from other projects like [Todo.txt](http://todotxt.org/).

Due dates are dates, without times.  They allow you to see what is on your agenda for the day.

Ultralist does not try to dictate your exact schedule, and therefore a todo's
due date does _not_ include a specific time.  However, you can prioritize todos
so that they take precedence over other todos.

#### Prioritization

You can prioritize a todo.  This will make it show as bold in the CLI, and
denotes that this todo is more important than others.

#### Archiving

Once todos are completed, you can archive them.  They won't show up anymore when listing todos.


