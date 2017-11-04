BPD - Pure data abstraction library
====

To include, you can do one of two things:

#### Add the abstractions directory to the PD Search Path
This will let you easily use any of the abstractions in any Pure Data project
  - `Pd -> Preferences -> Path...`
  - add the BPD/abstractions directory to your path


#### Include all of the necessary BPD abstractions in your project
This is not reccommended because some of the abstractions depend on each other, so you might need to include more than you expect.


SubPatches with UI
======
| name | use |
| ---- | ---- |
| BPD_adsr | An ADSR envelope with UI and inlet controls |
| BPD_btn-dsp |  Turn on/off DSP vis UI or inlet |
| BPD_btn-record | Stylized button |
| BPD_comb | Comb filter with inlet controls |
| BPD_dsp | Turn on/off DSP vis UI or inlet |
| BPD_fft | Linear FFT with UI and inlet controls |
| BPD_midisynth | A basic all-in-one kind of synth with adsr and vibrato |
| BDP_out1 | Small output with volume control |
| BDP_out2 | Output with volume, dsp, and pan controls |
| BPD_pan | A panner |
| BPD_player | Open and play audio files |
| BPD_reverb | A simple reverb |
| BPD_scope | An oscilloscope (SEE THE SOUND WAOW) |
| BPD_spectrum | A spectrum visualizer |
| BPD_strings | A karplus-strong string synth |
| BPD_timer | A big display that converts ms to m:s:ms |
| BPD_timer-mini | A small display that converts ms to m:s:ms |
| BPD_vibrato | Modulate sound with vibrato |
| BPD_waveshape | Make sounds |
| BPD_waveshape-mini | Make sounds, but probably via inlet ctrl |


SubPatches for calculation
=========
| name | use |
| ---- | ---- |
| BPD_digitsplit | Split number into digits |
| BPD_mtoc | Midi to cent |
| BPD_ftoc | Frequency to cent |

SubPatches for control
==========
| name | use |
| ---- | ---- |
| BPD_midikeys | Use your computer keyboard as a piano keyboard |
| BPD_switch | Turn it on, turn it off |
