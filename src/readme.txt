Readme für Planik:
=================

Unser angepasste Code ist unter https://github.com/planik/spine/tree/planik_branch zu finden

Version 1.6.2.xx vom 23.02.2023
- ajax.coffee geändert, damit URLS mit Parameter wie '/pflegehotel-st-johann/pflege/dienste?portal_identifier=MITARBEITERPORTAL'
  auch für einzelne Model-Objekte funktionieren

Version 1.6.2 vom 8. Dezember 2016
- spine.coffee geändert: changeID. Siehe  https://github.com/spine/spine/issues/611

Version vom 1.3.0 vom 1. März 2016 (Master)

ACHTUNG: Als ich auf coffeescript (NEUE VERSION) wechselte (kam mit Rails 4.7.1), so gab es einen Fehler in
route.coffee:
    match = @route.exec(path)
    return false unless match

@routes war undefined.
Wahrscheinlich muss man die neue Version von Spine runterladen...


old
V 1.1.0 Master Branch vom 31. Mai
Ich habe die .coffee Version geladen, damit SourceMaps zwischen js und coffee möglich sind.