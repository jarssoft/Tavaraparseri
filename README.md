# Tavaraparseri
Tavaravirtojen tilastointi kierrätyskeskukselle ym.

Ohjelmalla voidaan luokitella päivittäisiä tavaraeriä hierarkisiin ryhmiin esim. niiden käyttötarkoituksen mukaan.  
Ohjelma soveltuu kierrätyskeskukseen, kirpputorille, tai vaikkapa yksityishenkilön tarpeeseen.
Data voidaan viedä taulukkolaskentaan tarkempaa tilastointia varten.

Ensin tavaroista luodaan päivittäinen lista:

13.6.
pannu
lautasia 5 kpl
lusikka
lakana
2 tyynynpäällistä

14.6.
10 kirjaa
setteri
Rattaat

Sitten lista luokitellaan luokitustiedoston mukaan. Paketissa löytyy luokitustiedosto coicop (käyttötarkoituksen mukaan),
mutta käyttäjä voi tehdän oman luokituksen.

Ohjelma tunnistaa tavarat hakusanojen mukaa, jonka jälkeen se ilmoittaa tunnistettujen määrän, listaa tunnistetut ja
tunnistamattomat tavarat omina taulukoinaan.

Tavaramäärät voi viedä taulukkolaskentaohjelmaan (Excel tai LibreOffice) HTML-muodossa.

<table cellpadding="2" cellspacing="2">
	<tr>
		<th style="border: none; padding: 0cm"></th>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>Kaikki 
			</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>VAATETUS JA JALKINEET 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Vaatetus 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Kankaat 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Vaatteet 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Asusteet ja muut vaatetustarvikkeet 
			</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>Asusteet 
			</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>Muut vaatetustarvikkeet 
			</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>Ompelutarvikkeet 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Jalkineet 
			</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>ASUMINEN, VESI, SÄHKÖ, KAASU JA MUUT POLTTOAINEET 
			</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>KALUSTEET, KOTITALOUSKONEET JA YLEINEN KODINHOITO 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Huonekalut ja kalusteet, matot ja muut lattianpäällysteet 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Huonekalut ja kalusteet 
			</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>Olohuoneen ja ruokailuhuoneen kalusteet 
			</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>Makuuhuoneen kalusteet 
			</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>Valaisimet 
			</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>Muut huonekalut ja kalusteet 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Matot ja muut lattianpäällysteet 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Kodintekstiilit 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Kodintekstiilit 
			</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>Sisustuskankaat ja verhot 
			</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>Vuodevaatteet 
			</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>Huovat, viltit ja päiväpeitot 
			</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>Tyynyt ja peitot 
			</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>Vuodevaatteet 
			</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>Pöytäliinat ja pyyhkeet 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Kodinkoneet 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Lasitavarat, astiat ja kotitaloustarvikkeet 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Lasitavarat, astiat ja kotitaloustarvikkeet 
			</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>Lasi-, kristalli-, keramiikka- ja posliinitavarat 
			</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>Ruokailuvälineet 
			</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>Ruokailuvälineet, veitset, haarukat, lusikat 
			</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>Ei-sähköiset keittiövälineet 
			</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>Pannut ja kattilat 
			</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>Paistinpannu 
			</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>Kattila 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Kodin ja puutarhan työkalut ja laitteet 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Pienet työkalut ja erilaiset lisävarusteet 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Taloudenhoitoon liittyvät tavarat ja palvelut 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Kodin kulutustavarat 
			</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>Siivous- ja puhdistustuotteet 
			</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>Muut kodin kulutustuotteet 
			</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>TERVEYS 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Lääkevalmisteet, hoitolaitteet ja -välineet 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Muut lääkevalmisteet 
			</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>Silmälasit ja piilolinssit 
			</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>Muut hoitolaitteet ja -välineet 
			</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>LIIKENNE 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Ajoneuvon hankinta 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Polkupyörät 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Yksityisajoneuvojen käyttö 
			</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>VIESTINTÄ 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Postipalvelut 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Puhelin- ja telekopiolaitteet 
			</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>KULTTUURI JA VAPAA-AIKA 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Audiovisuaaliset laitteet, valokuvauslaitteet ja
			tietojenkäsittelylaitteet 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Äänen ja kuvan vastaanottoon, tallentamiseen ja toistoon
			käytetyt laitteet 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Valokuvaus- ja elokuvalaitteet ja optiset laitteet 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Tietojenkäsittelylaitteet 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Tallennusvälineet 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Muut kulttuuriin ja vapaa-aikaan liittyvät kestokulutustavarat
						</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Vapaa-aikaan liittyvät kestokulutustavarat sisäkäyttöön,
			mukaan lukien soittimet 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Muut vapaa-aikaan liittyvät tarvikkeet ja laitteet, puutarhat
			ja lemmikkieläimet 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Pelit, lelut ja harrastusvälineet 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Urheilu- ja retkeilyvälineet 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Puutarhat, kasvit ja kukat 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Lemmikkieläimet ja niihin liittyvät tuotteet 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Sanomalehdet, kirjat ja paperitavarat 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Kirjat 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Sanoma- ja aikakauslehdet 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Sekalaiset painotuotteet 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Paperitavarat ja piirustustarvikkeet 
			</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>MUUT TAVARAT JA PALVELUT 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Henkilökohtainen hygienia 
			</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>Henkilökohtaiset esineet, muualla luokittelemattomat 
			</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>Vauvanvarusteet 
			</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>LUOKITTAMATTOMAT 
			</p>
		</td>
	</tr>
	<tr>
		<th style="border: none; padding: 0cm">
			<p>2016-06-13</p>
		</th>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>18</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>16</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>10</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>10</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>6</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
	</tr>
	<tr>
		<th style="border: none; padding: 0cm">
			<p>2016-06-14</p>
		</th>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>91</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>5</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>39</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>19</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>19</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>15</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>14</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>9</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>6</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>34</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>8</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>6</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>6</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>5</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>20</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>16</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>4</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>6</p>
		</td>
	</tr>
	<tr>
		<th style="border: none; padding: 0cm">
			<p>2016-06-15</p>
		</th>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>62</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>20</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>4</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>4</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>14</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>14</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>9</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>5</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>11</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>10</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>9</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>7</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>7</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>23</p>
		</td>
	</tr>
	<tr>
		<th style="border: none; padding: 0cm">
			<p>2016-06-16</p>
		</th>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>75</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>29</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>7</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>6</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>4</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>4</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>4</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>15</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>15</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>15</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>27</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>12</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>9</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>14</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>14</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>7</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>6</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>8</p>
		</td>
	</tr>
	<tr>
		<th style="border: none; padding: 0cm">
			<p>2016-06-17</p>
		</th>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>123</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>84</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>24</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>24</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>20</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>47</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>47</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>32</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>8</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>8</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>7</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>6</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>6</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>6</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>14</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>11</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>10</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>8</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>6</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>15</p>
		</td>
	</tr>
	<tr>
		<th style="border: none; padding: 0cm">
			<p>2016-06-20</p>
		</th>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>48</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>20</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>7</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>7</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>7</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>10</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>10</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>10</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>17</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>9</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>8</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>8</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>4</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>4</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>9</p>
		</td>
	</tr>
	<tr>
		<th style="border: none; padding: 0cm">
			<p>2016-06-21</p>
		</th>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>94</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>4</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>4</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>4</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>41</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>12</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>12</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>9</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>3</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>24</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>24</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>22</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#ffbdbd" style="background: #ffbdbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdd7ff" style="background: #bdd7ff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>27</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>1</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>18</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>13</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>5</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>7</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>5</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#f2bdff" style="background: #f2bdff" style="border: none; padding: 0cm">
			<p>2</p>
		</td>
		<td bgcolor="#f2ffbd" style="background: #f2ffbd" style="border: none; padding: 0cm">
			<p>0</p>
		</td>
		<td bgcolor="#bdffd7" style="background: #bdffd7" style="border: none; padding: 0cm">
			<p>19</p>
		</td>
	</tr>
</table>

