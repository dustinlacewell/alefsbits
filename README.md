# alef's bits

![plugin screenshot](/screenshot.png "plugin screenshot")

a small collection of my VCV Rack modules in a single plugin. [click here](https://github.com/alefnull/alefsbits/releases) for the latest release.

## lights

a simple set of 8 inputs with corresponding lights. if latch mode is enabled, a gate/trigger will toggle the corresponding light on/off. if latch mode is disabled, the light will remain on while the input is high (>5V).

## poly play

polyphonic sample player. load sample through right click menu, then choose a number of channels to use. trigger input or button will play the sample, cycling through the available channels with each subsequent trigger.

## probably not

mutes a mono or poly input signal on trigger, based on probability

## logic

perform logical operations on two inputs

## math

applies various math operations on two inputs, clamped to +/-10V

## mlt

two 1:3 polyphonic multiples

## shift

analog shift register with cv-controllable probability per step

## oct sclr

scales voltage to specified octave range

## steps

a simple 8-step sequencer with a randomize trigger input and end-of-cycle trigger output. select output range in right-click menu.

## fibb

a simple clock divider based on the Fibonacci sequence of numbers.

## noize

a simple random noise generator with a duration parameter and optional 0-10V cv input.

## polyrand

a simple module that takes a trigger input and a polyphonic input, and outputs a random channel from that polyphonic input with each trigger, holding it's last output until the next trigger.

## simplex & hold

a simple sample & hold module using an internal simplex noise source. range parameter sets output range (+/-1, +/-3, or +/-5). use a polyphonic trigger input to output multiple samples at once.

## blank 6hp

a simple 6hp blank panel.
