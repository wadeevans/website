---
sidebar_label: el.saw
---

# el.saw(rate)

Outputs a naive sawtooth oscillator at the given frequency. Expects exactly one child
specifying the cycle frequency in `hz`.

Typically, due to the aliasing of the naive sawtooth at audio rates, this oscillator
is used for low frequency modulation.
