# Docker cluster implementing a website, using Postgres, Django and Nging with optional logging

Here's my quick setup and solution for the task.
I must apologise in advance because I know it doesn't work. I haven't even run it because I couldn't get Docker working on my laptop, so it stands a purely theoretical excercise.

## Docker Compose
The real meat of what I'm demonstrating. Proper configuration of what's running in the containers; of the containers themselves and their relation to each other; and some reliability and resilience measures. And of course clear, concise and easy to update and modify.

## Postgres, Django and Nginx
Without being able to run it I have only given them the most basic of setups, ready to be modified but inadequetely configured to work with each other. Nginx is pretty much just a template, Postgres just a random table with data I tried to use, and Django's programming is incomplete.

## Logging
The optional logging solution I'm confident would work properly, as it's very similar to what I worked with before. However depending on the syslog output of the other containers, Logstash could become necessary too.
