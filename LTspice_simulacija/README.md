# LTspice_simulacija

Ovaj folder sadrži fajlove za LTspice simulaciju Clock Oscilatora.

## Sadržaj
- ClockOscilator.asc — LTspice šema
- TL072.lib — biblioteka za korišćeni model operacionog pojačavača

## Kako pokrenuti
1. Pokrenite .asc fajl u LTspice programu (http://www.analog.com/ltspice).
2. Promenite .lib komandu tako da pokazuje na TL072.lib fajl na vašem računaru. 
3. Pokrenite simulaciju u okviru LTspice-a (kliknite na zelenu strelicu ili "run simulation").
4. Kada se simulacija pokrene pritisnite levim klikom na v-out i simulacija će prikazati signal u obliku pravougaonog talasa.
5. Daljom promenom otpornosti R4 otpornika, koji predstavlja potenciometar, i kapacitivnosti kondenzatora možete uticati na frekvenciju izlaznog signala.
