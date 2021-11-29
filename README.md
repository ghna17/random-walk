# random-walk
An Empirical Scientific Question…
How old is the sunlight that we see on Earth?
The short and easy answer that you may remember from science class is that it takes about 8 minutes for sunlight to reach the Earth. But, that 8 minutes is just the second part of a much longer and more interesting journey
(https://sunearthday.nasa.gov/2007/locations/ttt_sunlight.php). It only counts the time from when the light leaves the Sun and travels, in a straight line through the vacuum of space, to the Earth. Before it could even begin that journey, the light
had to first travel from near the center of the Sun to the surface of the Sun. In this first part of light's journey, from the center of the Sun to its surface, the light is constantly redirected in random directions by collisions with the particles that make up the Sun. Thus, it bounces around, taking a very indirect and random path from the center of the sun to its
surface. That random path, it turns out, takes a surprisingly long time. In this lab we will be using scientific simulations to generate an estimate of just how long. 

Brownian Motion
To get to the missing time that we need to answer our question we are going to pull in something else you learned about in science class, Brownian Motion. Brownian motion is named after Robert Brown, a botanist, who in 1827 described
particles of plant pollen moving around randomly in water and seemingly of its own volition. Over 75 years later, Albert Einstein hypothesized that these pollen particles were actually moving the way they did because they were being bounced
around by collisions with water molecules. 

Random Walk Algorithms
Computer simulations often model Brownian Motion as a random walk (https://en.wikipedia.org/wiki/Random_walk) using the following algorithm:
repeat the following some number of times
 turn in a random direction
 take one step forward

For such a simple process, there are an amazing variety of applications that use random walk algorithms (https://en.wikipedia.org/wiki/Random_walk#Applications). A few examples include:
• Models of the stock marked are based on the Random Walk Hypothesis (https://en.wikipedia.org/wiki/Random_walk_hypothesis), which posits that stock prices in an efficient market can
be modeled as a random walk.
• Biologists who study population genetics have modeled Genetic Drift (https://en.wikipedia.org/wiki/Genetic_drift) and Neutral Evolution (https://en.wikipedia.org/wiki/Neutral_theory_of_molecular_evolution) using random walks.
• Twitter's Who-To-Follow (WTF) (https://www.researchgate.net/publication/262318036_WTF_the_who_to_follow_service_at_Twitter) algorithm uses random walks as one part of how it recommends users you might be interested in following.
And most relevant to our present work:
• Astronomers use random walks to model the movement of light photons in the sun (http://www.astronoo.com/en/articles/journey-of-the-photon.html).

Thus, in this project we will collect and analyze data from computer simulations of random walks to generate an estimate of how long it takes for the light to travel, via random walk, from the center of the sun to its surface. Combining that with the
time we already know will give us an answer to our question. 

Simulating a Random Walk
Ultimately we will need to build a program that simulates random walks. However, in programming it is usually easier to build the program in smaller pieces. That way, each piece is relatively easy to build compared to the whole program and it
is also easier to check if each piece is working correctly. Then the pieces can be put together into the full program. This is called problem decomposition; it's a common problem solving strategy in computer science. 
