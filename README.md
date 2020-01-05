# Simple particle filter algorithm

# Introduce

This is GitHub code to learn particle filtering

Based on the original algorithm, I add a little improvement, focusing on finding high-quality particles.

After the particles are sorted according to the weight, the low weight (probability distribution function is higher than 0.5) is discarded. The high weight heavy particles sample their weight. The particles whose weight and probability distribution function are between 0.5 are evenly sampled, that is to say, the tendency of most particles is discovered

It is found that the effect is faster and more accurate, and it is not easy to lose.
