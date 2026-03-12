# Grundlagen einer Firewall

Eine Firewall überwacht und filtert den Netzwerkverkehr basierend auf definierten Regeln.
Es gibt Paketfilter (Layer 3/4), Stateful Inspection (berücksichtigt Verbindungszustände) und Next-Generation Firewalls (inkl. Applikationsinspektion).
Regeln bestehen oft aus Quelle, Ziel, Protokoll/Port und Aktion (Allow/Deny).
Standardprinzip „Default Deny“: Alles verbieten, nur benötigte Verbindungen explizit erlauben.
Zonen- und Segmentierungskonzepte (LAN, DMZ, WAN) reduzieren Angriffsflächen.
Logs und Alerts sind wichtig für Monitoring und Incident Response.
Regelpflege (Review, Cleanup, Change-Management) beugt Regelwildwuchs vor und erhöht Sicherheit.
