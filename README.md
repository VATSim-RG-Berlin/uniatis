UniATIS for RG Berlin
=======
Folgende variablen stehen zur verfügung:

ALLE AIRPORTS:

&depfreq=xxx.xxx

trägt man dort die Aktuell gültige Departure Frequenz ein wird diese in der ATIS wie bisher auch genannt nur mit dem unterschied das das Rufzeichen auch angesagt wird also zum Beispiel "Departure Frequency Bremen Radar on 123.225". Dabei erkennt das System automatisch anhand der Frequenz ob es UNICOM, DEPARTURE, ARRIVAL, BREMEN-, MÜNCHEN- oder RHEIN RADAR ausgeben soll. Es ist ganz egal ob 123.225 oder 123.220 angegeben wird.

&charts

Fügt "CHARTS AVAILABLE FOR FREE ON WWW.VATSIM-GERMANY.ORG" hinzu.

Tegel:

&bridge

bewirkt das "TAXIWAY PAPA ECHO AND BRIDGE CLOSED DUE TO WORKS IN PROGRESS TAXIWAY TANGO ROMEO CLOSED" in der ATIS enthalten ist. Diejenigen die dies gerne simulieren möchten wissen ja wo sie suchen müssen um raus zu finden ob die Brücke offen oder geschlossen ist.

Brandenburg:

&ila

Fügt ein "STANDBY WHEN CHECK IN FREQUENCY" in die ATIS mit ein.

&depn07

Fügt nach dem TRL ein "SIMULTANEOUS DEPENDANT ILS APPROACHES IN PROGRESS ON RUNWAYS 07L AND 07R" ein.

&depn25

Fügt das Gegenstück "SIMULTANEOUS DEPENDANT ILS APPROACHES IN PROGRESS ON RUNWAYS 25L AND 25R" ein.

Leipzig: (Gabor hatte da ein paar Wünsche :-) )

&parking08

Fügt "AIRCRAFT WITH PARKING POSITION ON APRON 1 OR 3 EXPECT DEPARTURE AND ARRIVAL RUNWAY 08L" zur ATIS hinzu.

&parking26

Fügt das Gegentsück "AIRCRAFT WITH PARKING POSITION ON APRON 1 OR 3 EXPECT DEPARTURE AND ARRIVAL RUNWAY 26R" hinzu.

&scenery

Fügt "ON INITIAL CALL ALL FLIGHTS TO LEIPZIG HALLE MUST REPORT SCENERY IN USE!"

Wenn man also In Tegel sitzt und Arrival online ist und die Brücke geschlossen ist würde der Link so aussehen:

http://uniatis.net/atis.php?arr=$arrrwy($atisairport)&dep=$deprwy($atisairport)&apptype=ILS&info=$atiscode&metar=$metar($atisairport)&bridge&depfreq=119.625

Den Approach Typ kann man übrigens auch ändern:

ILS = ILS
VOR/DME = VOR
NDB/DME = NDB
LOC/DME = LOC
Visual = VIS 
