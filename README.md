## twokenize

### Python standalone tokenizer for social media

This code takes strings of English, and splits them into lists of words.
It's designed to be tougher than other tokenizers, and cope with the kind of noise you seen on social media.

### Goals

Social media and Python have grown and shifted since the original release of this tool.
We have kept upgrading our versions at the University of Sheffield for some time, but this is better done as a community effort.
The result is this repo.
We'd like to be able to tolerate as broad a range noisy, user-generated text as possible, while keeping up to date with recent Python versions.

### Origin

This code is derived from Alan Ritter's implementation of the tokenizer:
  https://github.com/aritter/twitter_nlp

Which in turn is derived from TweetMotif:
  http://tweetmotif.com/about

