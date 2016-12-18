Radio Intelligence
====
######  Score: 300 + 200(share)

We had an intensive intelligence operation on the enemy radio. We know that they use LPCM with a sample rate of 16 kHz and 16 bits per sample (little endian). Also an LFSR is used for scrambling, with 16 bits or 32 bits of state.

There is an eavesdropping attached. Our agents are sure that it began with saying "The flag is", then, there is a delay for one or two seconds, and finally, the flag is said.

**Hint:** When the radio is supposedly silent, it actually includes a small amount of noise. Try brute forcing the noise values. These values are usually small, e.g., in the set {-8, ..., +8}.
