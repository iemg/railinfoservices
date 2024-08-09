<style>
    .container-lg {
    max-width: 90%;
    }
    div {
    overflow: scroll;
    position: relative;
    }

    table {
    position: relative;
    border-collapse: collapse;
    }

    td,
    th {
    padding: 0.25em;
    }

    thead th, tbody tr td:first-child {
    position: -webkit-sticky; /* for Safari */
    position: sticky;
    top: 0;
    background: #DDD;
    }

    thead th:first-child, tbody tr td:first-child  {
    left: 0;
    z-index: 1;
    }

    tbody th,, tbody tr {
    position: -webkit-sticky; /* for Safari */
    position: sticky;
    left: 0;
    background: #FFF;
    border-right: 1px solid #CCC;
    }
@media only screen and (max-width: 750px) {
    .container-lg {
      max-width: 100%;
    }
    .px-3 {
      padding-left: 8px !important;
      padding-right: 0px !important;
    }
}
</style>

# European railway information services

| Country | [🔎/🎫](## "Routing/Ticket") | [⏱️](## "Delay information") | [🏫](## "Arrival/departure boards") | [📍](## "Live map") | [🗺️](## "Maps") | [📖](## "Timetables") | [🚧](## "Works and disruptions") | other tools |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
| 🌎🌍🌏 | | | | | [OpenRailwayMap](https://www.openrailwaymap.org)<br>[allrailmap](https://allrailmap.com) | [📖 archive](https://timetableworld.com) | | [OSM Train Route Analysis](http://osmtrainroutes.bplaced.net/index.php) |
| EU 🇪🇺 | [🔎 DB](https://www.bahn.de/buchung/start?intern=1)<br>[🔎 ÖBB](https://fahrplan.oebb.at/webapp/)| | | [travic.app](https://travic.app)<br>[geOps](https://mobility.portal.geops.io/) |[railroadmaps (former bueker.net)](https://websites.umich.edu/~yopopov/rrt/railroadmaps/)<br>[nachtzugkarte.de](https://nachtzugkarte.de) |  | | [consists vagonweb.cz](https://vagonweb.cz)<br>[trip tracking](https://viaduct.world) |
| AL 🇦🇱 | [🔎🎫](https://hekurudha.al) | | | | | [📖](https://hekurudha.al) | | |
| AT 🇦🇹 | [🔎 ÖBB](https://fahrplan.oebb.at/webapp/)<br>[🔎 ÖBB old](https://fahrplan.oebb.at/bin/query.exe/dn)<br>[🎫 ÖBB](https://shop.oebbtickets.at/)<br>[🔎 VAO](https://anachb.vor.at) | [⏱️  live](https://fahrplan.oebb.at/bin/trainsearch.exe/dn?protocol=https:&)<br>[⏱️ archive](https://www.oebb.at/de/fahrplan/verspaetungsbestaetigung) | ÖBB Infra [I 👀](https://liveoebb.streamlit.app/stationboards) [II 👀](https://oebb-abfahrten.glitch.me)<br>[ÖBB HAFAS](https://fahrplan.oebb.at/bin/stboard.exe/dn) | [📍](https://www.zugradar.at) | [ÖBB Infra](https://infrastruktur.oebb.at/de/geschaeftspartner/schienennetz/dokumente-und-daten/netzkarten/karte-oebb-netz.pdf)<br>[lines Ostregion](https://www.oebb.at/de/regionale-angebote/wien) | [📖](https://www.oebb.at/de/fahrplan/fahrplanbilder) | [🚧 map](https://fahrplan.oebb.at/bin/help.exe/dn?tpl=showmap_external)<br>[🚧 list](https://www.oebb.at/en/fahrplan/baustelleninformation.html) | [consists](https://live.oebb.at/)|
| BA 🇧🇦 | [🔎🎫 ŽFBH](https://www.zfbh.ba/en/)<br>[🔎 ŽRS](http://www.zrs-rs.com)
| BE 🇧🇪 | [🔎🎫 SNCB/NMBS](https://www.belgiantrain.be/)<br>[🔎🎫 SNCB int.](https://www.b-europe.com/EN/Booking/Tickets?autoactivatestep2=false&traveltype=TwoWay&outbound=&outboundt=0&outboundtp=DepartureTime&inbound=&inboundt=0&inboundtp=DepartureTime&comfortclass=2&compactQsm=false&ticketlanguage=&travelparty=%257B%2522P%2522%253A%255B%257B%2522T%2522%253A%2522A%2522%252C%2522BDT%2522%253A%2522%2522%257D%255D%252C%2522M%2522%253Afalse%257D#TravelWish) | [⏱️ live](https://www.belgiantrain.be/en/travel-info/current/search-by-train-number?)<br>[⏱️ archive](https://www.belgiantrain.be/en/support/customer-service/delay-certificate) | [🏫](https://www.belgiantrain.be/en/travel-info/current/search-by-station) | [📍](https://trainmap.acc-belgiantrain.be) | [🗺️](https://www.belgiantrain.be/fr/travel-info/prepare-for-your-journey/leaflets/lines-leaflets) | [📖](https://www.belgiantrain.be/fr/travel-info/prepare-for-your-journey/leaflets/lines-leaflets) | [🚧](https://www.belgiantrain.be/en/travel-info/current/ongoing-disturbances-and-works) | [consists👀](https://www.beluxtrains.net/en/index.php?page=compositions)
| BG 🇧🇬 | [🔎](https://razpisanie.bdz.bg/en)<br>[🎫](https://bileti.bdz.bg) | [⏱️](https://www.bdz.bg/en/live-updates) | [🏫](https://live.bdz.bg/en) | [📍](https://radar.bdz.bg/en) | 
| BY | [🔎](https://www.rw.by) 
| CH 🇨🇭 | [🔎 ](https://www.oev-info.ch/)<br>[🔎🎫 SBB](https://www.sbb.ch/en) | [⏱️](https://www.sbb.ch/en/travel-information/rail-traffic-information/cnfirmation-delay.html) | [🏫👀](http://chill.serena-mueller.ch) | [📍](https://maps.trafimage.ch/ch.sbb.netzkarte?layers=ch.sbb.puenktlichkeit-gondola,ch.sbb.puenktlichkeit-funicular,ch.sbb.puenktlichkeit-ferry,ch.sbb.puenktlichkeit-bus,ch.sbb.puenktlichkeit-tram,ch.sbb.puenktlichkeit-nv,ch.sbb.puenktlichkeit-fv&baselayers=ch.sbb.netzkarte,ch.sbb.netzkarte.dark,ch.sbb.netzkarte.luftbild.group,ch.sbb.netzkarte.landeskarte,ch.sbb.netzkarte.landeskarte.grau&lang=de&x=948835.29&y=6002200.99&z=11.04)<br>[📍👀](https://maps.vasile.ch/transit-sbb/) | [🗺️ lines](https://www.oev-info.ch/de/fahrplan-aktuell/liniennetzplaene-netzgrafiken) | [📖](https://www.oev-info.ch/de/fahrplan-aktuell/fahrplanarchiv)<br>[Graphic timetables](https://www.oev-info.ch/de/fahrplan-aktuell/grafische-fahrplaene) | [🚧](https://www.sbb.ch/content/internet/sbb/en/reiseinformationen/bahnverkehrsinformation/betriebslage-stoerungen.html?bbox=eyJ0b3AiOls1LjczNDkwMDAwMDAwMDY5Miw0NS4yMTI4MjQ4MzY4Nzg2OTZdLCJib3R0b20iOlsxMC42Njc3MDAwMDAwMDA3MzUsNDguMzU2MzkyODc2NDIzMDNdfQ%253D%253D) | [Travel times 👀](https://fuerstenberger.shinyapps.io/minimal_travel_times/)<br>[punctuality map 👀](http://puenktlichkeit.ch)<br>[station punctuality map 👀](http://puenktlichkeit.ch)
| CZ 🇨🇿 | [🚆🔎 SŽ](https://najdispoj.spravazeleznic.cz)<br>[🚆🎫 OneTicket](https://oneticket.cz/home)<br>[🚆🔎🎫 ČD](https://www.cd.cz/en/spojeni-a-jizdenka/)<br>[🚆🎫 Regiojet](https://regiojet.cz/)<br>[🚆🎫 LeoExpress](https://www.leoexpress.com/en)<br>[🚆🚌 IDOS](https://idos.idnes.cz/vlakyautobusymhdvse/spojeni/) |[⏱️ČD](https://cd.cz/vlak/)<br>[⏱️Regiojet](https://regiojet.cz/aktuality-z-provozu/zpozdeni?delayCityId=372825000&delayType=departure)<br>[⏱️LeoExpress](https://www.leoexpress.com/en/current-information) | [🏫](https://www.spravazeleznic.cz/cestujici/infotabule) | [SŽ](https://mapy.spravazeleznic.cz/vlaky-provoz)<br>[GRAPP (more filters)](https://grapp.spravazeleznic.cz) | [SŽ PDF](https://provoz.spravazeleznic.cz/Portal/ViewArticle.aspx?oid=2104272)<br>[SŽ (interactive)](https://mapy.spravazeleznic.cz/vlaky) | [📖](https://www.spravazeleznic.cz/cestujici/jizdni-rad) | [SŽ planned](https://mapy.spravazeleznic.cz/stavby)<br>[ČD](https://cd.cz/jizdni-rad/omezeni-provozu/) | [locos 👀](http://sledovani.55p.cz) |
| DE 🇩🇪 | [🔎🎫](https://www.bahn.de/buchung/start?intern=1) | [⏱️ live](https://mobile.bahn.de/bin/mobil/trainsearch.exe/dox?webview=&)<br>[⏱️ archive👀](https://www.zugfinder.net/) | [🏫](https://www.bahnhof.de)<br>[🏫👀](https://trainboard.de.cool) | | [lines](https://www.bahn.de/service/fahrplaene/streckennetz)<br>infra [I](https://geovdbn.deutschebahn.com/isr) [II](https://geovdbn.deutschebahn.com/pgv-map/client/gisclient/index.html?applicationId=1179651) | [📖](https://kursbuch.bahn.de/hafas/kbview.exe/dn?rt=1&mainframe=tab_main) | [live infra](https://strecken-info.de)<br>[live passenger](https://www.bahn.de/service/fahrplaene/aktuell)<br>[planned](https://bauinfos.deutschebahn.com/)<br>[planned long-distance](https://bauinfos.deutschebahn.com/fernverkehr) | [📖 fernbahn.de👀](https://www.fernbahn.de/datenbank/suche/)<br>[trassenfinder.de](https://trassenfinder.de/)<br>[bahn.expert👀](https://bahn.expert)
| DK 🇩🇰 | [🔎🎫](https://www.dsb.dk/trafikinformation/koereplaner/) | | | | [🗺️](https://www.dsb.dk/trafikinformation/koereplaner/koreplaner-strakningskoreplaner-pdf/)  | [📖](https://www.dsb.dk/trafikinformation/koereplaner/koreplaner-strakningskoreplaner-pdf/) | [🚧](https://www.dsb.dk/trafikinformation/andringer-i-trafik-og-drift/andringer-i-trafik-og-drift/)
| EE 🇪🇪 | [🔎🎫](https://elron.ee) | | | | | [📖](https://elron.ee/en/soiduinfo/soiduplaanid) | [🚧](https://elron.ee/en/soiduinfo/teated)
| ES 🇪🇸 | [🔎 RENFE](https://www.renfe.com/es/en/travel/informacion-util/horarios)<br>[🎫 RENFE](https://www.renfe.com/es/en) | | | | [🗺️](https://www.renfe.com/es/en/travel/informacion-util/mapas-y-lineas/ave-y-larga-distancia) | | [🚧](https://www.renfe.com/es/en/renfe-group/communication/renfe-today/alerts)
| FI 🇫🇮 | [🔎🎫](https://www.vr.fi/en) | [⏱️](https://www.vr.fi/en/on-track)<br>[⏱️👀](https://juliadata.fi/live) | | [📍](https://www.vr.fi/en/on-track)<br>[📍👀](https://juliadata.fi/map/view?mode=trains#7/) | | [📖](https://www.vr.fi/en/timetables) | [🚧 live](https://www.vr.fi/en/on-track/traffic-news)<br>[🚧 planned](https://www.vr.fi/en/on-track/planned-track-work)
| FR 🇫🇷 | [🔎🎫](https://www.sncf-connect.com/en-en/) | | [🏫](https://www.garesetconnexions.sncf/fr/gares-services) | [📍👀](https://carto.tchoo.net) | [infra map](https://www.sncf-reseau.com/fr/cartes/carte-du-reseau-ferre-national)<br>[infra atlas](https://www.sncf-reseau.com/fr/cartes/atlas-du-reseau-ferre-francais) |  | [🚧](https://www.sncf-voyageurs.com/fr/voyagez-avec-nous/horaires-et-itineraires/informations-trafic/gl/)
| GB 🇬🇧 | [🔎🎫](https://www.nationalrail.co.uk) | [⏱️👀](https://www.realtimetrains.co.uk) | [🏫](https://www.nationalrail.co.uk/live-trains/departures/) | [📍👀](https://www.map.signalbox.io/) | [🗺](https://www.nationalrail.co.uk/travel-information/maps-of-the-national-rail-network/) | [📖](https://www.networkrail.co.uk/running-the-railway/the-timetable/electronic-national-rail-timetable/) | [🚧](https://www.nationalrail.co.uk/status-and-disruptions/)<br>[🚧 Eurostar](https://www.eurostar.com/rw-en/travel-info/travel-updates) | [Track diagrams👀](https://www.opentraintimes.com/maps)<br>[consists👀](https://www.realtimetrains.co.uk)
| GR 🇬🇷 | [🔎🎫](https://tickets.hellenictrain.gr/dromologia/?lang=en)<br>[🔎🎫 (only some routes)](https://newtickets.hellenictrain.gr/Channels.HellenicTrainWeb/) | | | | | | [🚧](https://www.hellenictrain.gr/en/announcements)
| HU 🇭🇺 | [🔎🎫](https://jegy.mav.hu) | | | [📍](https://vonatinfo.mav-start.hu/map.aspx?browser=1) | [🗺](https://www.mavcsoport.hu/mav-start/media/terkepek) | [📖](https://www.mavcsoport.hu/mav-start/belfoldi-utazas/menetrendek) | [🚧](https://www.mavcsoport.hu/mav-start/belfoldi-utazas/vaganyzar)
| HR 🇭🇷 | [🔎🎫](https://prodaja.hzpp.hr/en/Ticket) | [⏱️](https://www.hzpp.app/?trainId=4061) | | | [🗺️](https://eng.hzinfra.hr/?page_id=418) | [📖](https://www.hzpp.hr/vozni-red?m=743&mp=17) | [🚧 HŽPP nat.](https://www-hzpp-hr.translate.goog/radovi-na-pruzi?p=275&_x_tr_sl=hr&_x_tr_tl=en&_x_tr_hl=nl&_x_tr_pto=ajax,elem)<br>[🚧 HŽPP int.](https://www.hzpp.hr/en/train-on-time-2?p=361&r=72&mp=78)
| IE 🇮🇪 | [🔎🎫](https://www.irishrail.ie/en-ie/) | [⏱️](https://www.irishrail.ie/en-ie/travel-information/your-travel) | [🏫](https://www.irishrail.ie/en-ie/train-timetables/live-departure-train-times) | [📍 DART](https://www.irishrail.ie/en-ie/train-timetables/dart-live-map)<br>[📍 Commuter](https://www.irishrail.ie/en-ie/train-timetables/commuter-live-map)<br>[📍 Intercity](https://www.irishrail.ie/en-ie/train-timetables/intercity-live-map) | | [📖](https://www.irishrail.ie/en-ie/train-timetables/timetables-by-route) | [🚧](https://www.irishrail.ie/en-ie/news/irishrail-engineering-works) |
| IT 🇮🇹 | [🔎🎫](https://www.lefrecce.it/Channels.Website.WEB/) | [⏱️](http://www.viaggiatreno.it/infomobilita/index.jsp) | | | | | [🚧 map](http://www.viaggiatreno.it/infomobilita/index.jsp#)<br>[🚧 list](https://www.trenitalia.com/it/informazioni/Infomobilita/notizie-infomobilita.html)<br>[🚧 list by region](https://www.trenitalia.com/it/informazioni/lavori_e_modifichealservizio/ricerca.html)
| LT 🇱🇻 | [🔎🎫](https://www.vivi.lv/en/) | | | | [🗺️](https://www.vivi.lv/en/information-for-passengers/route-scheme-zoning/) | [📖](https://www.vivi.lv/en/information-for-passengers/)
| LU 🇱🇺 | [🔎](https://www.cfl.lu/en-gb/timetable) | | | | | [📖](https://www.cfl.lu/en-gb/timetable) | [🚧](https://www.cfl.lu/de-de/works) | [consists👀](https://www.beluxtrains.net/en/index.php?page=compositions)
| LV 🇱🇹 | [🔎🎫](https://bilietas.ltglink.lt) | | | | [🗺️](https://ltglink.lt/en/route-map) 
| MD 🇲🇩 | [🔎🎫](https://on.railway.md:10000/?lang=en)
| ME 🇲🇪 | [Trains from Skopje](https://mzt.mk/poagane-od-skopje/)<br>[Trains to Skopje](https://mzt.mk/pristigane-vo-skopje/)<br>[prices](https://mzt.mk/цени-по-релации/) | | | | | [📖](https://mzi.mk/en/timetable/)
| MK 🇲🇰 | [🔎](https://zpcg.me/en) | | | | | [📖](https://zpcg.me/en/red-voznje/ukupno)
| NL 🇳🇱 | [🔎🎫 9292.nl](https://9292.nl/en)<br>[🔎🎫 NS](https://www.ns.nl/en/travel-information) | |  [🏫](https://www.ns.nl/en/travel-information) | | [infra](https://infrabel.be/en/networkstatement) | | [🚆🚌🚧](https://9292.nl/en/messages)<br>[🚆🚧 live](https://www.ns.nl/en/travel-information/current-situation-on-the-tracks/)<br>[🚆🚧 nat. planned](https://www.ns.nl/en/travel-information/maintenance-on-the-tracks/)<br>[🚆🚧 int.](https://www.nsinternational.com/en/overview-service)
| NO 🇳🇴 | [🔎🎫](https://entur.no) | | | | | [📖](https://www.vy.no/trafikk-og-ruter/rutetider) | [🚧](https://www.banenor.no/reise-og-trafikk/trafikkmeldinger/)
| PL 🇵🇱 | [🔎 PKP](https://portalpasazera.pl/en/Wyszukiwarka/Index)<br>[🔎🎫 bilkom](https://bilkom.pl)<br>[🎫 KOLEO](https://koleo.pl) | [⏱️](https://portalpasazera.pl/en/Opoznienia/Index?s=4)  | [🏫](https://portalpasazera.pl/en/Plakaty) | [📍](https://portalpasazera.pl/en/MapaOL) | | [📖](https://portalpasazera.pl/en/Tablice/RozkladWformieTablic)
| PT 🇵🇹 | [🔎](https://www.cp.pt/passageiros/en/train-times)<br>[🎫](https://www.cp.pt/passageiros/en/buy-tickets) | | | | | |[🚧](https://www.cp.pt/passageiros/en/train-times/Alerts)
| RO 🇷🇴 | [🔎🎫 nat.](https://bilete.cfrcalatori.ro/en-GB/Itineraries)<br>[🎫 int.](https://bileteinternationale.cfrcalatori.ro/en/booking/search) | [⏱️](https://bilete.cfrcalatori.ro/en-GB/Trains) | [🏫](https://bilete.cfrcalatori.ro/en-GB/Stations)
| RS 🇷🇸 | [🔎](https://w3.srbvoz.rs/redvoznje/info/en) | | [🏫](https://w3.srbvoz.rs/redvoznje/info/en) | | | [📖](https://www.srbvoz.rs/en/timetable-kurir/) | [🚧](https://w3.srbvoz.rs/redvoznje)
| SE 🇸🇪 | [🔎🎫](https://www.sj.se/en/search-journey/search/departure-station/arrival-station/departure-date) | | | [1409.se👀](https://1409.se/trains/Rst)<br>[traincheck.se👀](https://www.traincheck.se) | | | [🚧](https://www.sj.se/en/traffic-information)
| SI 🇸🇮 | [🔎](https://potniski.sz.si/en/timetable-finder/)<br>[🎫](https://eshop.sz.si) | [⏱️](https://potniski.sz.si/en/help-and-travel-updates/#delays)| | [📍](https://potniski.sz.si/en/help-and-travel-updates/#active-trains-display) | [🗺️](https://potniski.sz.si/en/plan-your-journey/map-rail/) | | [🚧](https://potniski.sz.si/en/help-and-travel-updates/#rail-replacement-buses)
| SK 🇸🇰 | [🔎 ŽSR](https://tis.zsr.sk/elis/pohybvlaku)<br>[🔎 ZSSK](https://www.zssk.sk/en/)<br>[🎫 ZSSK](https://predaj.zssk.sk/search) | [⏱️ ŽSR (all)](https://tis.zsr.sk/elis/pohybvlaku)<br>[⏱️ Regiojet](https://regiojet.sk/aktuality-z-prevadzky/meskanie-spojov) | [🏫](https://aplikacie.zsr.sk/TabuleZsr/) | [📍](https://mapa.zsr.sk/index.aspx) |  | [📖](https://www.zssk.sk/cestovny-poriadok/) | [🚧](https://aplikacie.zsr.sk/MapaVylukZsr/index.aspx) | [train delays👀](https://meskanievlakov.info)
| TR 🇹🇷 | [🔎🎫](https://ebilet.tcddtasimacilik.gov.tr/view/eybis/tnmGenel/tcddWebContent.jsf) | | | |[🗺️👀](https://railturkey.org/wp-content/uploads/2020/10/turkiye-demiryollari-haritasi-2019.jpg)
| UA 🇺🇦 | [🔎🎫](https://booking-new.uz.gov.ua/en) | [⏱️](https://uz-vezemo.uz.gov.ua/delayform) | [🏫](https://booking-new.uz.gov.ua/en/schedule)

<!-- Bonus: [Tokyo Metro and Suburban Trains👀](https://minitokyo3d.com/) -->

nat. = national  
int. = international  

👀 = third party tools/links