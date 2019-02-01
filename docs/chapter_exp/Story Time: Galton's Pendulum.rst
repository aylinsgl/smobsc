Story Time: Galton's Pendulum
-----------------------------

In the 1880s, scientific progress had opened up a novel entertainment option for
Her Majesty Queen Victoria’s subjects: have their psychometric traits measured
in Francis Galton's Science Galleries, at the South Kensington Museum. Visitors
paid "3 pence" (presumably some sort of currency) and then partake in a series
of encounters with novel and strange machinery. Thousands of participants
volunteered, establishing one of the first large-sample psychometric databases
in history. Amongst the things measured was how long it took the curious museum
goer to press a button in response to a simple light stimulus.

Galton measured response times using an ingenious design called the
`Pendulum chronograph`_. Simplified, the position of a swinging pendulum at the
time point of a key-press could be compared to a reference table. This Galton
used as an estimate of response time, which allowed a state of the art
resolution of 1/100th of a second. Never before had mental process been
measured with higher precision.

.. figure:: figures/galtons_instruments.png
	    :alt: galtons instruments

	    Some of Galton's tools. The pendulum chronograph is more complicated than any of these!

	    Public domain image taken from (citation missing).

.. _Pendulum chronograph: http://galton.org/essays/1880-1889/galton-1889-rba-reaction-time.pdf

Other experimenters around this time were stopping response latencies with
manual stopwatches. Galton himself conducted human geographic surveys by
walking around London, mentally rating the women he saw for their
attractiveness, and covertly noting the ratings with a self made device: a
paper cross, into which he, in his pocket, punched a hole indicating if the
woman was of below average, average, or above average "beauty".

It is not advised to mention such practices in a contemporary presentation of
scientific results. At the very least, the practices would be seen as grossly
inaccurate, and for many, highly open to experimenter bias. In particular, they
lack precision. Also, to be frank -- they sound like a lot of work! While some
might decry a lack of entrepreneurial spirit, most of us will readily admit the
advantage of computerized methods.

Progress has made the work of the researcher much simpler. (Remember this
sentence whenever you feel frustrated attempting to program an experiment! At
least you are not Galton, keeping a pendulum chronograph in working condition,
or walking across London to mentally file people into rather crude and
subjective boxes.) Today, computers can show various visual input, play all
kinds of sounds, and accurately measure ... well, a narrow kind of behavioral
responses made by experimental participants. Our computer's graphics and sound
cards, and the keyboard and mouse drivers, are relatively arcane. There is as of
yet no convenient way to get a computer to show words or pictures on a screen
for the purposes of psychological experiments from our favourite programming
language, R. There are many commercial, closed-source solutions, which we will
all ignore in favour of the powerful and open Python options.

Why? Perhaps the most important benefit computerized experiments have is that
they are much more reproducible. Using an Open Source program and making
experimental stimuli and scripts available online allows other researchers to 1.
exactly retrace what happened in the original experiment, 2. repeat it ad
libitum. To actually exploit this reproducibility potential, we must use
software that is open. The biggest open source experimental presentation
software is Psychopy (:cite:`peirce2007psychopy`).
