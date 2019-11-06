# Update - 2019-11-06

This repo (described below and available on its various forks) has run its
course, and so I've force-pushed a change to remove its history.

It originally contained 100 years worth of auto-generated commits, starting on
Jan 1 1970. Each day through year 2069 contained between 3 and 10 commits. The
contents of the commits were generated from FreeBSD's fortune.

This was done as an experiment. It was fun, but based on a few comments this
repo has received, I believe it to be more annoying than fun for most people
who stumble into it. Worse than annoying, I'm afraid some people have
misattributed the quotes and associated date of commit to be some sort of
authoritative source, which is of course absurd.

Further, it is messy for people doing searches on github.

If I were to just remove this repo, one of its forks would become
authoritative. Instead, I've decided to just force push a single commit to the
repo. This should fix the internet for the most part, as far as its concerned
with oh_my_fortune.

If you'd like to see the contents this repo used to have, take a look at one of
its forks.

# FAQ

This repo is kind of weird. I've received a lot of questions about it, and so I
thought I would try to clear things up a bit.

## How are you committing every day? 

While there are commits every day, they've already been made through year 2069.
GitHub merely thinks they may have just happened, because git.

## How were you using git in the 1970's?

The real question is, why doesn't git handle pre-epoch time?

## It's kind of offensive, isn't it?

I hope so, otherwise -o is a lie. To quote FreeBSD's
[FORTUNE(6)](https://github.com/freebsd/freebsd/tree/master/usr.bin/fortune):

     -o      Choose only from potentially offensive aphorisms.  Please,
             please, please request a potentially offensive fortune if and
             only if you believe, deep down in your heart, that you are will-
             ing to be offended.  (And that if you are not willing, you will
             just quit using -o rather than give us grief about it, okay?)

                   ... let us keep in mind the basic governing philosophy
                   of The Brotherhood, as handsomely summarized in these words:
                   we believe in healthy, hearty laughter -- at the expense of
                   the whole human race, if needs be.
                   Needs be.
                                              --H. Allen Smith, "Rude Jokes"

## Cute. So really, what's the deal?

I was curious how GitHub would deal with irrational time. Would my "Longest
streak" be 46 years, or 100? (46 years, or 17,000 or so days). How would it
deal with future commits? (it considers all future events "just now"). In other
words, it was just for the fun of being able to confidently say that I have the
longest GitHub streak in the world, even if it is contrived.
