### audio and filter capacitors  
capacitors which are located directly within the audio signal path or in audio filter circuits\*,  
The most difficult and delicate components when it comes to NOT affecting the sound quality.  
(read this series of engineering- and sience- based articles if you don't believe that capacitors can affect sound quality -> <a href="https://github.com/analoghifi/capacitors/tree/main/audio%20and%20filter%20capacitors/docs/capacitor%20sound">capacitor sound</a>)

   
#### main requirements:
 - non polarized capacitor  
 - non-polar dielectric
 - very low dissipation factor "tan δ" (= low loss) (e.g. tanδ = 0.0002 .. 0.0006 \[@1kHz\] or better)\*\* \[the lower the better\]
 - lowest possible frequency dependency of the dissipation factor (within the audio range)  
 - high accuracy (important for filter circuits\* only - e.g. 1%)  
 - lowest possible frequency dependence of the capacitance
 - lowest possible voltage dependence of the capacitance (in terms of DC-Bias- and AC-voltage)  
 - NO piezoelectric effect / microphonic effect at all  
 - lowest possible capacitor self-inductance (ESL)

.    
  
<strong>suitable dielectrics</strong> for these requirements are:  
 - Polypropylene \[KP/MKP\]  
 - Polystyrene (a.k.a."Styroflex") \[KS\]  
 - Mica (a.k.a "Glimmer")  
 - C0G (NP0) -ceramic  
 - Polysulfone  
 - PTFE

(the last two mentioned are almost impossible to find on the market)  
.    
  
film/foil constructions \[KP/KS\] usually show better performance than metallized film types \[MKP\], in terms of the dissipation factor "tan δ" (lower and less frequency dependent),  
but film/foil types are not always available these days especially with higher capacitance values (then we choose good \[MKP\]-types).   
  
  
\*(filter circuits like RIAA-filters (RIAA-preamps), active crossovers and passive crossovers)  
\*\*( tanδ:&nbsp;&nbsp;&nbsp;0.0002 .. 0.0006 == 0.02% .. 0.06% == 0.2x10<sup>-3</sup> .. 0.6x10<sup>-3</sup> == 2x10<sup>-4</sup> .. 6x10<sup>-4</sup> )  

----
#### better MKP's:
in recent years, MKP capacitors have become better and better, and in some cases are in no way inferior to KP (film/foil) capacitors  
e.g.:  
* all Mundorf MKP Series  tanδ = 0.0002 @ 1kHz
* RIFA (now KEMET) PHE 425 \[1% tol. available\] tanδ = 0.0003 @ 1kHz
* Vishay MKP 1837 \[1% tol. available\] tanδ = 0.0004 @ 1kHz
* Vishay MKP 1839 \[1% tol. available\] tanδ = 0.0004 @ 1kHz  

bigger ones:
* KEMA PHE 450 tanδ = 0.0003 @ 1kHz
* KEMA PHE R76 tanδ = 0.0003 @ 1kHz
* KEMA PHE R75H tanδ = 0.0004 @ 1kHz
* KEMA PHE 426 tanδ = 0.0005 @ 1kHz
* WIMA MKP2 tanδ = 0.0005 @ 1kHz
* WIMA MKP4 / MKP10 tanδ = 0.0006 @ 1kHz
  
only "high-end" KP capacitors (film/foil) can still surpass this, but these are almost no longer available on the market  
e.g:
* CDE WPP-Series (you cannot read the exceptionally low tanδ value from the data sheet / only measurements reveal it)
* Mundorf MCap ZN Classic tanδ = 0.00002 @ 1kHz (factor 10 better than the best MKP's)


----
#### old (NOS) WIMA KP Series:  
the old (NOS) WIMA KP (film/foil) Series FKP02 / FKP2 / FKP3 / FKP4 are better (lower tanδ) than the new ones:  
(compare the datasheets)  
* old = NOS = "New Old Stock" -> non ROHS conform: [old FKP2](https://github.com/analoghifi/capacitors/blob/main/audio%20and%20filter%20capacitors/docs/datasheets/kp/WIMA_FKP_2__OLD_nonROHS__EN.pdf) / [old FKP3](https://github.com/analoghifi/capacitors/blob/main/audio%20and%20filter%20capacitors/docs/datasheets/kp/WIMA_FKP3_OLD_nonROHS__EN.pdf)  
* new -> ROHS conform: [new FKP2](https://github.com/analoghifi/capacitors/blob/main/audio%20and%20filter%20capacitors/docs/datasheets/kp/WIMA_FKP_2__NEW_ROHS__EN.pdf) / [new FKP3](https://github.com/analoghifi/capacitors/blob/main/audio%20and%20filter%20capacitors/docs/datasheets/kp/e_WIMA_FKP_3.pdf)

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
