December 17, 2017

Last edited: Sep 8, 2025

> This article is part of my [audiophiles](../) series of articles

# Audio fidelity

## Definition

[Here](https://sonicscoop.com/2014/04/24/defining-audio-fidelity),
Ethan Winer defines audio fidelity for you:

> Sound, for all the nuance and excitement it offers,
> only operates in two dimensions: Time and intensity.
>
> In turn, only four parameters are needed to assess
> everything that affects audio fidelity.

Sound is 2D wave, and we usually only need 4 parameters to judge overall performance.

## Noise

Anything not present in the source material is called noise.

If the input is silence, but there's a hiss in the output, that hiss is noise.
If the input is a 0dBFS 1kHz tone, but the output has some other components like
sidebands at 5khz and 2kHz, the sum of those components constitute noise.

Noise is bad because it coexists with the main signal, degrading it by masking.

We can measure noise in dB below our main signal. Ideally, we want a system with
noise level ~100dB lower than the main signal. This means that we'll have to crank
up the volume over 100dB just to hear 0-1dB of noise.

Most audio devices these days are very good in the noise department, thanks to
improvements in engineering and prevalence of other noise-sensitive electronics
that required engineers to fix noise issues.

Only truly shitty audio products have noise level lower than 80dB.

## Frequency response

A *flat* response means that your system, when fed signals of varying frequencies
but of the same amplitude, will output the same amplitude for all frequencies.

If the response is not flat, then the output signal will have different amplitude.
If there's a dip, then the amplitude at the dip frequencies will be lower (quieter).
If there's a peak or a boost in the bass range response, lower frequencies will be
louder, resulting in warmer, bassier sounds.

The ideal frequency response is is a flat line across audible range. Most audio
devices today are flat, except for transducers like speakers and headphones.

## Distortion

How audio signal may distort, i.e. incorrectly manifest. There're many types of
distortion, but we'll focus on two: harmonic distortion and
intermodulation distortion (IMD).

[Harmonic distortion](https://en.wikipedia.org/wiki/Distortion#Harmonic_distortion)
is when the output features some weird tones at frequencies that are multiple to
the input signal. Most harmonic distortion is "2nd harmonic", i.e. at 2x the input frequency.

Due to how our brain and ear works, harmonic distortion may sound ok or even pleasant
to the ear, because it's somehow musically related to the input signal.

We can sum up all of those harmonic distortion into [Total Harmonic Distortion (THD)](https://en.wikipedia.org/wiki/Total_harmonic_distortion),
usually expressed as percentage e.g. 1% THD. Some measurements also show THD and noise
as a parameter: THD+N, usually expressed as dBFS.

[Intermodulation distortion](https://en.wikipedia.org/wiki/Intermodulation) is a different beast.
IMD is a result of amplitude modulation of different input frequencies.

Unlike harmonic distortions, IMD manifests across the frequency band and sounds very bad because
the noise is musically not related the input tone. IMD is, like THD, expressed as THD.

A 1% THD is much better than 1% IMD.

## Time-based errors

Since sound is naturally a longitudinal wave with time as one of its axis,
large time-based errors *will* affect other parameters.

An example would be analog audio's *wow* (cassete tape standard ~ 0.08%)
or digital audio jitter (although I personally treat jitter as noise because
of how fast the timing errors are).

## Conclusion

"These four basic parameters define everything that affects audio fidelity.
As powerful as it is, there's no secret "magic" to sound, no unknown parameters
that "science" hasn't yet learned to identify, as is sometimes claimed.

The closer an audio signal is to the source across these four parameters,
the higher its fidelity." - Ethan Winer

We want our audio gear to have the best fidelity possible, so we focus on
minimizing noise, distortion, and time-based errors, while keeping the response flat.
