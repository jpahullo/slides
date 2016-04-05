# Gitlab

by *Jordi Pujol Ahulló* 

[@jpahullo](http://twitter.com/jpahullo)

Presented on [2016-04-20](http://www.meetup.com/Tarragona-Developers-Meetup/events/229781981/)

[Tarragona Developers Meetup](http://www.meetup.com/Tarragona-Developers-Meetup/) 

[@tgndevs](http://twitter.com/tgndevs)

----

## Project manager

*Everything starts with an issue*

---

## gitlab.com for free 

- unlimited public projects
- unlimited private projects

---

## Community Edition (CE)

- Totally free
- No restrictions
- Not all features available

---

## Enterprise Edition (EE)

- gitlab.com version
- payment version
- full-featured

----

# Installation

- From source code
- From .deb .pkg packages
- From docker image

----

# Community Edition preview

image

----

But only a project manager?

----

# Continuous Integration

- Gitlab CI integrated with Gitlab
- Per project
- Every push produces a build

http://doc.gitlab.com/ce/ci/README.html

---

# But... How?

A simple keyword

**runners**

---

# A runner is

- a Gitlab's [registered client](http://doc.gitlab.com/ce/ci/runners/README.html)
- [installed on any computer](https://gitlab.com/gitlab-org/gitlab-ci-multi-runner/#install-gitlab-runner)

image of types of installations

---

# A runner waits

- requests from Gitlab to run tasks
 * unitary tests
 * integration tests
 * ...
 * whatever defined in *.gitlab-ci.yml* file.

---

# Runners are integrated from Gitlab

- Gitlab shows whether it was ok
- Rerun build on demand
- Depicts which computer is committing the build

---

# When installing a runner

You decide the execution type of builds

- shell
- docker
- docker-ssh
- ssh

---

# Runner types

### Shared

- Proceeding builds from any project (default)
- Use tags to describe requirements

### Specific

- You manually assign runners to projects

----

# Demo

----

# Thanks!

[@jpahullo](http://twitter.com/jpahullo/)

http://jpahullo.github.io/slides/gitlab/
