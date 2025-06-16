# perlweekly2pod

[On Reddit recently](https://www.reddit.com/r/perl/comments/1lah0a7/perl_podcasts/)
there was some discussion of Perl podcasts. T. Alex Beamish mentioned the Perl
Weekly and Olaf Alders suggested someone could record themselves reading it.

This conversation was mentioned in
[issue #725](https://perlweekly.com/archive/725.html) of the Perl Weekly and
Gabor tied that back to my recent blog post about
[Generating Content with ChatGPT](https://perlweekly.com/archive/725.html)
and suggested:

> would it be possible to have some Perl script that would take the content
> of the Perl Weekly newsletter and using some AI tool would generated a
> podcast out of it? Any volunteers?

Of course it would. And this code is a proof of concept. The steps are:

1. Ask ChatGPT to script a conversation based on the content of an issue of
   Perl Weekly
2. Use a text-to-speech service 
   (I've used [ElevenLabs](https://elevenlabs.io/)) to turn that into an MP3

There are a couple of sample episodes in the repo.
