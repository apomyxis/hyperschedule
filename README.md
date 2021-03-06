**Hyperschedule**: the fast course scheduler.

## Live demo

Check out https://hyperschedule.herokuapp.com!

## API

We have one! Hit up

    https://hyperschedule.herokuapp.com/api/v1/all-courses

You'll find it more enjoyable than Portal.

## Why?

This scheduler takes a different approach to the various versions of
**hmc-scheduler**, and this approach makes it much faster to amend
your schedule on the fly during registration. Also, half-semester
courses finally work :)

## Local development

    $ yarn
    $ pip3 install -r requirements.txt
    $ ./server.js

## Run in production mode

    $ yarn babel
    $ ./server.js --production

## Contributing

This is essentially a hackathon project so coding standards are not
high. I will merge pull requests readily. Or, you can open an issue
for a bug or feature request.
