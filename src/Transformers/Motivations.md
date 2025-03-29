# Motivations for Transformers


## What problem do Transformers solve

### RNNS

The longer the chain of computation the more derivates are multiplied together.

The concern is when you have gradients betweeen -1 and 1 or when your numbers are large. 

Why ?

Slow updates
You GPU CPU can only represent numbers up to a certain precision. I.e 32 bit or 64 bit 

Context far back in the network matters 


