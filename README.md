# dialect-writing
R script to produce dialectal spellings based on phonological features in the North of England, e.g. ‘happy’ > ‘happeh’ (reflecting super-lax happY vowel in Manchester English).

Features included: 

* (ing), e.g. walking > walkin
* (td)-deletion, e.g. just > jus
* (th)-fronting, e.g. tooth > toof
* (th)-stopping, e.g. that > dat
* (h)-dropping, e.g. happens > appens
* happY-laxing, e.g. city > citeh
* AW-to-UW, e.g. town > toon
* T-to-K, e.g. bottle > bockle
* T-to-R, e.g. got a > gorra
* general consonantal reduction, e.g. doesn’t > dunt
* general vocalic reduction, e.g. yourself > yerself

Takes the CMU pronouncing dictionary as input (http://www.speech.cs.cmu.edu/cgi-bin/cmudict) and adds frequency counts from the SUBTLEX-UK corpus (http://crr.ugent.be/archives/1423).

Script used for the analysis presented in:

Nini, Andrea, George Bailey, Diansheng Guo & Jack Grieve. *to appear*. The graphical representation of phonological dialect features of the North of England on social media. In Patrick Honeybone & Warren Maguire (eds.), *Dialect writing and the North of England*. Edinburgh: Edinburgh University Press.

