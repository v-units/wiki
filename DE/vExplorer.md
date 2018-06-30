# Beschreibung des vExplorers #

Der vExplorer visualisiert die Daten, Bewegungen und Veränderungen in der Blockchain, den Nodes und den Wallets.

## Menüposition &quot;Units&quot;: ##

Bei &quot;Address&quot; ist die Empfänger- und Absenderadresse der Wallets angegeben. &quot;Balance&quot; zeigt die Menge der vUnits in dem betreffenden Wallet an.

## Menüposition &quot;Shares&quot;: ##

Bei &quot;Address&quot; ist die Empfänger- und Absenderadresse der Wallets angegeben. &quot;Balance&quot; zeigt die Menge der vShares in dem betreffenden Wallet an (Erklärung siehe Whitepaper).

## Menüposition &quot;Parameters&quot;: ##

### General -&gt; Global: ###

Bald verfügbar.

### Trusted Parties -&gt; Audit: ###

Hier werden die Höhe der Kosten (in vUnits) eines Audits für Zertifizierungsstellen (LCA, LE, LPMD und LD) angezeigt.

### Emission -&gt; Parameters: ###

*__&quot;Percentage of Emission as Security&quot;__*  
Zeigt die Höhe des aktuell geforderten Depots in Prozent eines LE bei einer Emission an. Werden z.B. 10&#39;000 vUnits emittiert, muss der LE zum jetzigen Zeitpunkt ein Sicherheitsdepot von 500vUnits (entspricht 5%) hinterlegen. Nach abgeschlossener Emission erhält der LE das Depot zurück.

*__&quot;Emission Voting Period&quot;__*  
Gibt an, wie lange das Vetorecht der vShares maximal dauern kann. Dabei ist ein Block ca. 30 Sekunden, was aktuell gesamthaft maximal 7 Tagen entspricht.

*__&quot;Emission Voting Threshold&quot;__*  
Zeigt an, wie viele vShares gegen eine Emission stimmen müssen, damit das Veto gültig ist und die Emission abgelehnt wird.

*__&quot;Emission Rules&quot;__*  
Beschreibt den Emissionsalgorithmus.

### Voting -&gt; Parameters: ###

*__&quot;Parameter Change Petition Period&quot;__*  
Gibt an, wie lange eine Petition der vShares-Besitzer maximal dauert, wird der geforderte Prozentsatz (aktuell 66%) vorher erreicht, so geht die Petition in das Voting über, ist nach Ablauf der Blöcke der Prozentsatz nicht erreicht, so wird die Petition gelöscht.

*__&quot;Parameter Change Petition Threshold&quot;__*  
Zeigt prozentual an, wie viele DAFÜR-Stimmen der vShares für die Annahme der Petition benötigt werden.

*__&quot;Parameter Change Voting Period&quot;__*  
Gibt an, wie lange eine Abstimmung der verifizierten vWallet-Besitzer maximal dauert, bis die gewählten Stimmen der vWallet gezählt und ausgewertet werden. Dabei entspricht ein Block ca. 30 Sekunden.

*__&quot;Parameter Change Voting Threshold&quot;__*  
Zeigt prozentual der stimmenden vWallets an, wie viele DAFÜR-Stimmen für die Annahme der Abstimmung benötigt werden.

## Menüposition &quot;Variables&quot;: ##

### General -&gt; Global: ###

*__&quot;Total Gold&quot;__*  
Gibt die gesamte Menge Gold (in gr.) in der vUnits-Blockchain an.

*__&quot;Total Units&quot;__*  
Gibt die gesamte Menge vUnits in der vUnits-Blockchain an.

*__&quot;Total Shares&quot;__*  
Gibt die gesamte Menge vShares in der vUnits-Blockchain an.

*__&quot;Total Voters&quot;__*  
Gibt die gesamte Anzahl wahlberechtigter vWallets in der vUnit-Blockchain an.

*__&quot;Total Units in Fund&quot;__*  
Gibt die aktuelle Anzahl vUnits im VUF Fond an.

*__&quot;Total Units in Security&quot;__*  
Gibt die aktuell gesamte Menge der im Sicherheitsdepot befindenden vUnits an (Depot von LE)

*__&quot;Total Units in Destruction&quot;__*  
Gibt die gesamte Menge vUnits, welche sich im Zerstörungsprozess befinden (bzw. in Gold zurück gewechselt werden)

### Trusted Parties -&gt; Pending: ###

Hier werden die anfragenden zukünftigen Zertifizierungsstellen (wie LCA, LE, LPMD und LD) angegeben, welche mittels Audit und Abstimmung neu in die Blockchain aufgenommen werden wollen. Neben dem Namen der neuen potentiellen Parteien ist auch deren fixe öffentliche Blockchainadresse sowie der Zeitpunkt, bei welchem Block der Antrag zur Aufnahme in die Blockchain erfolgte, angezeigt.

### Trusted Parties -&gt; Confirmed: ###

In diesem Bereich sind alle autorisierten Parteien (wie LCA, LE, LPMD und LD) angegeben, sowie deren Angaben und der Zeitpunkt des Blocks, wann diese von der Community in die Blockchain gewählt wurden.

### Emission (Units) -&gt; Variables: ###

*__&quot;Last Emission on&quot;__*  
Zeigt den Block der letzten Emission an.

*__&quot;Last Emission Price&quot;__*  
Zeigt den letzten Emissionspreis an.

*__&quot;Last Emission Units&quot;__*  
Zeigt die Anzahl vUnits der letzten Emission an.

*__&quot;Emission Adjustment Period until&quot;__*  
gibt den Zeitraum (in Anzahl Blöcken) an, in welcher der Emissionspreis von &quot;Emission Adjustment Start Price&quot; zu &quot;Emission Adjustment End Price&quot; sinkt.

*__&quot;Emission Adjustment Start Price&quot;__*  
Gibt den neuen Preis direkt nach der letzten abgeschlossenen Emission an.

*__&quot;Emission Adjustment End Price&quot;__*  
Gibt den Preis nach Ablauf der *__&quot;Adjustment Period&quot;__* an.

### Emission (Units) -&gt; Pending: ###

Hier befinden sich aktuell in der Verarbeitung befindliche Emissionen. Dabei ist die Zieladresse der Emission beim Userwallet und die Adressen der beteiligten LE, LPMD und LD angezeigt. Weiter wird die Höhe des Sicherheitsdepots des LE angegeben sowie die maximale und effektive Menge Gold und die Anzahl vUnits, welche bei der Emission generiert werden. Zudem ist ersichtlich, bei welchem Block die Emission gestartet und beendet wurde und bei welchem Block LPMD und LD die Emission bestätigt haben. Ausserdem sieht man, wie viele Blöcke das Veto der vShares dauert und wie viele vShares dafür oder dagegen gestimmt haben.

### Emission (Units) -&gt; Completed: ###

Dito *__&quot;Emission (Units) -&gt; Pending__*&quot;. Mit dem Unterschied, dass hier die abgeschlossenen Emissionen aufgeführt werden.

### Emission (Shares) -&gt; Completed: ###

Bald verfügbar.

### Destruction (Units) -&gt; Pending/Completed: ###

Die Anzahl zu zerstörenden bzw. zerstörten vUnits werden hier angezeigt. Zudem sind die Adressen des betreffenden Wallets und des LD angezeigt. Weiter wird gezeigt bei welchem Block die Zerstörung vom User eingeleitet und vom LD bestätigt wurde.

### Parameter Changes -&gt; Pending/Completed: ###

In diesem Bereich werden alle laufenden und durch Abstimmung bestätigten Parameteränderungen aufgelistet. Die Initialisierungsadresse, der betreffende Parameter, der neue Wert, bis zu welchem Block wie viele vShares und vWallet dafür oder dagegen gewählt haben wird ebenfalls angezeigt.