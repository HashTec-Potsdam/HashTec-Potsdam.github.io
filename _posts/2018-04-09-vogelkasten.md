---
layout: post
title: Vogelkasten zum Zusehen
subtitle: Wir haben einen Brutkasten mit einem Raspberry-Pi versehen.
gh-repo: niccokunzmann/vogelhaus
gh-badge: [star, fork, follow]
---

Der Meisennistkasten hängt an einem Baum nahe der machBar im freiLand.
Noch sind keine Meisen eingezogen, vielleicht tun sie das aber noch.

An dem Nistkasten ist ein Raspberry-Pi Model A+ angeklebt.
Dieser befindet sich in einer Aufstrichdose,
damit er vor Wind und Wetter geschützt ist.
Er steuert eine Kamera an, um Bilder zu machen.
Diese stellt er über einen Web-Server bereit.

Ein Paar Daten:
- Computer: Raspberry Pi A+, 5V
- Kamera: Pi-Kamera
- Vogelhaus-Software: [niccokunzmann/vogelhaus]
- Web-Adresse: [vogelkasten.ffp.quelltext.eu]
- Beleuchtung: Infrarot-LED

Eigendlich war angedacht, einen [YouTube-Stream] zu machen.
Allerdings schickt dieser viele Daten, ohne dass wir sie nutzen.
Diesen haben wir von dem [Tutorial für die Infra-Rot-LED][tutorial].
Diese macht es möglich, das Haus zu beleuchten, ohne die Vögel zu stören.

Was noch aussteht ist eine dauerhafte Stromversorgung.


[niccokunzmann/vogelhaus]: https://github.com/niccokunzmann/vogelhaus
[vogelkasten.ffp.quelltext.eu]: http://vogelkasten.ffp.quelltext.eu
[YouTube-Stream]: https://youtu.be/bqxPMIo7t9s
[tutorial]: https://projects.raspberrypi.org/en/projects/infrared-bird-box
