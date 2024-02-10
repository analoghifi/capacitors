# capacitors  
choosing the right capacitors for our audio hifi projects...  

----
### audio and filter capacitors  
<a href="audio and filter capacitors">➔ open subdirectory</a>  
capacitors which are located directly within the audio signal path or in audio filter circuits\*,  
The most difficult and delicate components when it comes to NOT affecting the sound quality.  
(read this series of engineering- and sience- based articles if you don't believe that capacitors can affect sound quality -> <a href="https://github.com/analoghifi/capacitors/tree/main/audio%20and%20filter%20capacitors/docs/capacitor%20sound">capacitor sound</a>)  
   
#### main requirements:
 - non polarized  
 - non-polar dielectric
 - very low dissipation factor "tan δ" (= low loss) (e.g. tanδ = 0.0002 .. 0.0006 \[@1kHz\] or better)\*\* \[the lower the better\]
 - lowest possible frequency dependency of the dissipation factor (within the audio range)  
 - high accuracy (important for filter circuits\* only - e.g. 1%)  
 - lowest possible frequency dependence of the capacitance
 - lowest possible voltage dependence of the capacitance (in terms of DC-Bias- and AC-voltage)  
 - NO piezoelectric effect / microphonic effect at all
 - lowest possible capacitor self-inductance (ESL)

suitable dielectrics for these requirements are:  
Polypropylene \[KP/MKP\] | Polystyrene (a.k.a."Styroflex")\[KS\] | Mica (a.k.a "Glimmer") | C0G(NP0)-ceramic  

film/foil constructions \[KP/KS\] usually show better performance than metallized film types \[MKP\], in terms of the dissipation factor "tan δ" (lower and less frequency dependent),  
but film/foil types are not always available especially with higher capacitance values (than we choose good \[MKP\]-types).  
  
\*(filter circuits like RIAA-filters (RIAA-preamps), active crossovers and passive crossovers)  
\*\*( tanδ:&nbsp;&nbsp;&nbsp;0.0002 .. 0.0006 == 0.02% .. 0.06% == 0.2x10<sup>-3</sup> .. 0.6x10<sup>-3</sup> == 2x10<sup>-4</sup> .. 6x10<sup>-4</sup> )  

----
### blocking / bypass / decoupling -capacitors  
<a href="blocking or bypass capacitors">➔ open subdirectory</a>   
increasing the purity of DC by bypassing all unwanted (RF-) AC to ground,   
supporting the DC supply to be able to deliver very fast current peaks.  
#### main requirements:
 - non polarized  
 - lowest possible impedance at the frequency range we want to supress / bypass
 - lowest possible capacitor self-inductance (ESL)
 - t.b.d.
 - t.b.d.
----
### big electrolytic capacitors  
<a href="big electrolytic capacitors">➔ open subdirectory</a>   
The heart of our DC power supply, able to provide a stable DC level even when drawing huge current peaks.  
Supressing ("filter out") the remaining line frequency 50/60Hz ("hum") components, coming from the rectifier bridge, even at high loads.  
#### main requirements:
 - polarized  
 - very high capacitance (e.g. 1000µF .. 100000µF)
 - long life = \"mean time between failures\" (MTBF) 10000h or better \[the higher the better\]
 - high temperature resistance e.g. 105°C-types
 - very low ESR (=low impedance) @100Hz/120Hz (depending on the capacitance e.g. 15mΩ .. 50mΩ or better) \[the lower the better\]
 - capable of providing / withstanding high ripple currents @100Hz/120Hz  
 - lowest possible capacitor self-inductance (ESL)

all of this characteristics listed above are greatly improved by paralleling as many electrolytic capacitors as possible within a DC power supply ...  
