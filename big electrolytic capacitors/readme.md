### big electrolytic capacitors  
(common abbreviations: E-CAP, EC, ELCO \[german: 'ELKO'\])  

The heart of our DC power supply, able to provide a stable DC level even when drawing huge current peaks.  
Supressing ("filter out") the remaining line frequency 100Hz/120Hz* ("hum") components, coming from the rectifier bridge, even at high loads.  
#### main requirements:
 - polarized  
 - very high capacitance (e.g. 1000µF .. 100000µF)
 - long life = \"mean time between failures\" (MTBF)\*\* >5000h .. 10000h or better \[the higher the better\]
 - high temperature resistance e.g. 105°C-types
 - very low ESR (=low impedance) @100Hz/120Hz\* (depending on the capacitance e.g. 15mΩ .. 50mΩ or better) \[the lower the better\]
 - capable of providing / withstanding high ripple currents @100Hz/120Hz\*  
 - lowest possible capacitor self-inductance (ESL)

all of this characteristics listed above are greatly improved by paralleling as many electrolytic capacitors as possible within a DC power supply ...  

-----

Attention:  
sometimes the ripple current (and sometimes also the impedance/ESR?) is given at 100kHz in the data sheets  
usually there is a conversion table "MULTIPLIER FOR RIPPLE CURRENT" somewhere in the data sheet,  
so that you can calculate the value for operation at mains frequency (100Hz/120Hz)\* ...  
  
Or you can also take a comparative look at the tanδ that may be specified in some datasheets,  
whether that is specified at 100/120Hz and simply calcualte the ESR from the tanδ if necessary:  
tanδ = ESR * (2π * f * C)  
ESR = tanδ / (2π  *  f  *  C)  
Q = 1 / tanδ  
  
an example:  
figures for 'Rubycon' 63ZLJ2200M16X40 (ZLJ series): 2200uF 63V / 16×40mm / 4,1A ripple / Impedance(ESR) 15mOhm @ 100kHz / tanδ 0,09 @120Hz  
  
\*(frequency of the positive sine half waves afer the bridge rectifier)  

----

Some manufacturers, e.g. 'Krummer' sometimes write very conservative figures for MTBF\*\* in their datasheets,  
which relate to operation with nominal (high) ripple current and/or high temperatures,  
so take a close look at the data sheet there...  
e.g. the (105°C) series 'Krummer' 311LC and 313EC (ultra compact) have excellent values and MTBF\* rates if you read the data sheet carefully.  

\*\*(MTBF = \"mean time between failures\" = expected operating time of the capacitor (under its normal DC- and load-level))  

----

Understanding basic capacitor parameters:  
<a href="docs/related/Krummer_General_Information_Capacitor_Parameters_DE_EN.pdf">Krummer_General_Information_Capacitor_Parameters_DE_EN.pdf</a>  
see as well: https://www.wima.de/en/service/knowledge-base/basic-technical-data-of-capacitors/ (but more foil capacitor related)  
and:  
<a href="/What is a Capacitor - basic concepts and formulae.pdf">What is a Capacitor - basic concepts and formulae</a>  
from here -> <a href="https://www.electronics-notes.com/articles/basic_concepts/capacitance/capacitance.php">Original (7 Parts)</a>
