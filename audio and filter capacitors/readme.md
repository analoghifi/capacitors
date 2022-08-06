### audio and filter capacitors  
capacitors which are located directly within the audio signal path or in audio filter circuits\*,  
The most difficult and delicate components when it comes to NOT affecting the sound quality.  
(read this series of engineering- and sience- based articles if you don't believe that capacitors can affect sound quality -> <a href="https://github.com/analoghifi/capacitors/tree/main/audio%20and%20filter%20capacitors/docs/capacitor%20sound">capacitor sound</a>)

   
#### main requirements:
 - non polarized  
 - very low dissipation factor "tan δ" (= low loss) (e.g. tanδ = 0.0003 .. 0.0005 \[@1kHz\] or better)\*\* \[the lower the better\]
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
\*\*( tanδ:&nbsp;&nbsp;&nbsp;0.0003 .. 0.0005 == 0.03% .. 0.05% == 0.3x10<sup>-3</sup> .. 0.5x10<sup>-3</sup> == 3x10<sup>-4</sup> .. 5x10<sup>-4</sup> )  

----

tanδ = ESR * (2π * f * C)  
ESR = tanδ / (2π  *  f  *  C)  
Q = 1 / tanδ  

----

Understanding basic technical data of capacitors:  
https://www.wima.de/en/service/knowledge-base/basic-technical-data-of-capacitors/  
see as well: <a href="/big electrolytic capacitors/docs/related/Krummer_General_Information_Capacitor_Parameters_DE_EN.pdf">Krummer_General_Information_Capacitor_Parameters_DE_EN.pdf</a> (but more electrolytic cap related)  
and:  
<a href="/What is a Capacitor - basic concepts and formulae.pdf">What is a Capacitor - basic concepts and formulae</a>  
from here -> <a href="https://www.electronics-notes.com/articles/basic_concepts/capacitance/capacitance.php">Original (7 Parts)</a>  
