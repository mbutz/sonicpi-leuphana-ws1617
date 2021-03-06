# Übersicht der Sessions

Anmerkungen: Die mit "Referat" gekennzeichneten Themen sind Beiträge (Seminarleistungen) der TeilnehmerInnen. Zur Vorbereitung der Referate sollten die angegebenen Ressourcen ausgewertet werden. Natürlich können Sie zusätzlich auch auf eigene Quellen zurückgreifen. Alle weiteren genannten Themen werden vom Dozenten vorbereitet.

## Session 1: Einstieg

Datum: 18.10.2016

- Vorstellung der TeilnehmerInnen und des Dozenten
- Demo: Sonic Pi
- Organisatorisches
- Erste Klänge ('''play, sleep, live_loop''')

### Ressourcen

- Sonic Pi-Dokumentation "Tutorial" und "Beispiele"
- Blogbeitrag zu Sonic Pi anlässlich der Re:publica (Berlin, 2016) mit Vortrag, Folien und Code-Beispielen,  http://www.mkblog.org/2016/05/04/republica-ten-hoerbar-programmieren-mit-sonic-pi/
- Kyle Kingsbury: Core language concepts, https://aphyr.com/posts/266-core-language-concepts

## Session 2: Synthesizer in Sonic Pi, live_Loop, tick & look

Datum: 01.11.2016

- Referat: Synthesizer (Grundlagen, Bestand in Sonic Pi)
- `live_loop, tick, look`
- Pair Programming

### Referat

- Grundbegriffe der Klangerzeugung durch Synthesizer mit Hinblick auf Sonic Pi
    - Sinuston und Obertöne
    - Grundkomponenten eines Synthesizers (Oscillator, Filter, Amplifier, Envelope, LFO)
    - Wellenformen, Modulation, Hüllkurve, Filter
    - Additive und subtraktive Synthese
    - Synthesizer in Sonic Pi
    - Klangbeispiele mit Modifikationen der Hüllkurve
    - Demonstration und Erläuterung der ausgewählter Parameter (z. B. `synth :fm`)

### Ressourcen

- Sonic Pi-Dokumentation "2 Synths"
- Wolfgang Saus, Die Obertonreihe, http://www.oberton.org/obertongesang/die-obertonreihe/ 
- Sound on Sound, Synth Secrets, http://www.soundonsound.com/sos/allsynthsecrets.htm
- Overtones, harmonics and Additive synthesis, https://www.youtube.com/watch?v=YsZKvLnf7wU&list=PL0CF041F562C5BE5E
- ADSR envelope synth tutorial part A:  https://www.youtube.com/watch?v=A6pp6OMU5r8&list=PL0CF041F562C5BE5E&index=2
- ADSR envelope synth tutorial part B: https://www.youtube.com/watch?v=9niampRkFW0&index=3&list=PL0CF041F562C5BE5E
- A Young Person's Guide to the Principles of Music Synthesis by Beau Sievers http://beausievers.com/synth/synthbasics/

## Session 3: Samples in Sonic Pi, Musiktheorie

Datum: 15.11.2015

- Referat: Samples in Sonic Pi (Einbindung, Parameter, externe Samples)
- Nach Absprache im Seminar: Tonmaterial, Skalen, Akkorde (kurze Einführung in die Musiktheorie mit Sonic Pi)
- Pair Programming

### Referat

- Sampling
    - Grundbegriffe
    - Samples in Sonic Pi (Bestand, Parameter, Beispiele)
    - Einbindung externer Samples

### Ressourcen

- Sonic Pi-Hilfe zu `sample` etc. und Tutorial "3 Samples"
- "Can I Get Another Amen", Dokumentarfilm über den Amen Break von Nate Harrison, https://archive.org/details/NateHarrisonCanIGetAnAmen

## Session 4: Filter und Effekte in Sonic Pi, Organisation und Ablaufsteuerung von Code I

Datum: 29.11.2016

- Referat: Filter und Effekte in Sonic Pi
- Synchronisation von Live-Loops (Codebeispiele mit Erläuterungen)
- Pair Programming

### Referat

- Filter und Effekte in Sonic Pi
    - grundsätzliche Anwendung (`with_fx`) und ausgewählte Parameter
    - Klangbeispiele mit unterschiedlichen Filtern und Parametern

### Ressourcen

- Sonic Pi-Hilfe zu `with_fx` etc. und Tutorial "6 Effekte"
- Einführung in die Musiktheorie, kurze Einführung als PDF: http://www.2felsfrei.de/attachments/024_musiktheorie.pdf
- Music Theory for Musicians and Normal People, by Toby W. Rush, http://tobyrush.com/theorypages/



## Session 5: Elektronische Musik I, Organisation und Ablaufsteuerung von Code II

Datum: 13.12.2016

- Referat: Elektronische Musik am Beispiel von "Kontakte" von Karlheinz Stockhausen
- Wiederholung des Materials aus vorhergehenden Sessions (Tonfolgen, Effekte, `live_loop`, `in_thread` etc.)
- Pair Programming

### Referat

- Karheinz Stockhausen: Kontakte

### Ressourcen

- WDR3 Studio Elektronische Musik Stockhausen - Kontakte, Radio-Feature online:  https://www.youtube.com/watch?v=kBP1v29cx60
- Karlheinz Stockhausen (1978): Die vier Kriterien der elektronischen Musik, in: Texte zur Musik, Bd. 4, Köln: DuMont, S. 360-401; als Skript eines Vortrag vom 14.09.72 online: http://www.elektropolis.de/ssb_story_stockhausen.htm

## Session 6: Elektronische Musik II: Electronica, musikalische Analyse

Datum: 10.01.2017

- Referat: Elektronische Musik II, "Advice to clever children": Aphex Twin, Plasticman, Scanner, Daniel Pemberton u.a.
- Musikalische Analyse und Nachbau in Sonic Pi ([SonicVisualizer](https://github.com/mbutz/sonicpi-leuphana-ws1617/tree/master/sonic-visualiser), Codebeispiele und Erläuterungen zu Nachbau von [Digital Bubblebath](https://www.youtube.com/watch?v=Fy8h3kSef1E)/[Nachbau](https://soundcloud.com/mbutz/digital-bubblebath) und [Otaku](https://www.youtube.com/watch?v=OYusX7V1SaI)/[Nachbau](https://soundcloud.com/mbutz/otaku-1-from-series-rec-with-sonic-pi))
- Pair Programming

### Referat

- Text: "Advice to clever children" (Leitfragen: Welche Unterschiede in der Konzeption von 'elektronischer Musik' werden deutlich? Welche Gemeinsamkeiten gibt es?)

### Ressourcen

- Interview mit Karlheinz Stockhausen, 'Advice to clever children', "The Wire", November 1995, http://www.stockhausen.org/ksadvice.html
- Karlheinz Stockhausen, Gesang der Jünglinge, https://www.youtube.com/watch?v=nffOJXcJCDg

## Session 7: Offene Enden: Rückblick, Vorstellung der Arbeitsproben, Ausblick

Datum: 24.01.2017

- Vorstellung der vorläufigen Arbeitsergebnisse
- Rekapitulation
- Offene Fragen


## Allgemeine Ressourcen

**FACT Magazin, 3 Artikel zur Einführung in Werkzeuge zur Erstellung von elektronischer Musik**

The 14 most important synths in electronic music history – and the musicians who use them, John Twells, Sep 15 2016, http://www.factmag.com/2016/09/15/14-most-important-synths/

The 14 pieces of software that shaped modern music, by John Twells, Oct 1 2016, http://www.factmag.com/2016/10/01/the-14-pieces-of-software-that-shaped-modern-music

15 samplers that shaped modern music – and the musicians who use them, Laurent Fintoni, Sep 15 2016, http://www.factmag.com/2016/09/15/15-samplers-that-shaped-modern-music/

**Samples (Download)**

Freesound.org: Freesound aims to create a huge collaborative database of audio snippets, samples, recordings, bleeps, ... released under Creative Commons licenses that allow their reuse, http://www.freesound.org

Philharmonic Orchestra: Thousands of free, downloadable sound samples specially recorded by Philharmonia Orchestra players. These samples are suitable for creating any kind of music, no matter what style: http://www.philharmonia.co.uk/explore/make_music

59,413 free sample downloads (A to Z), The MusicRadar Team (01.10.2016), http://www.musicradar.com/news/tech/free-music-samples-download-loops-hits-and-multis-627820

Free Wave Samples: Free Wave Samples provides high-quality wav files free for use in your audio projects, http://freewavesamples.com/

Hiphop Production Resource & Free Samples, http://www.thesample.net/

FLStudioMusic offers one of the biggest archive of free sample packs featuring one-shots, sound effects, vocals, foley and much more. http://www.flstudiomusic.com/category/free-sample-packs

The Flipside (Forum), February 12, 2009 (ich weiss nicht, wie aktuell diese Liste ist), http://www.theflipsideforum.com/index.php?topic=11431.0

The Bedroom Producers Blog, an online magazine about cheap and affordable music making software, hardware and other music production tools. http://bedroomproducersblog.com/category/sample-packs/

**Akustik, Synthesizer, Klangsynthese**

How do Synthesizers work, http://www.explainthatstuff.com/synthesizers.html, (basale aber gut verständliche Einführung)

The Physics Hypertextbook. Music & Noise, Glenn Elert, http://physics.info/music/

Amplitude Modulation. An interactive demo which enables you to both see and hear the result of multiplying a sine wave with a cosine amplitude envelope, https://academo.org/demos/amplitude-modulation/

**Akustik, Klang, Musiktheorie**

Music Theory for Musicians and Normal People, Toby W. Rush, http://tobyrush.com/theorypages/

Professional music theory: an outline of basic music theory, by Oscar van Dillen ©2011-2016, http://www.oscarvandillen.com/outline_of_basic_music_theory/

**Kreativität & Ästhetik**

DeSantis, Dennis (2015): Making Music. 74 Creative Strategies for Electronic Music Producers, Berlin: Ableton.

Bense, Arne (2016): Live – eine gelöschte Unterscheidung, Blogbeitrag vom 12.08.2016, letzter Abruf am: 10.10.2016, https://netzpolitik.org/2016/live-eine-geloeschte-unterscheidung/
Was bedeutet eigentlich „live“? Obwohl die Beantwortung dieser Frage alles andere als trivial ist, geistert der Begriff durch die Welt der elektronischen Musik und trennt die Szene in elektronische Live- und DJ-Culture.

**Live Coding**

All things livecoding - A curated list of livecoding languages and tools, https://github.com/lvm/awesome-livecoding/

Bericht über Live-Coding im Deutschlandfunk vom 18.10.2016, http://www.deutschlandfunk.de/live-coding-konferenz-die-leute-koennen-sehen-wie-musik.807.de.html?dram:article_id=368890

Sam Aaron live coding a DJ set with Sonic Pi, https://www.youtube.com/watch?v=KJPdbp1An2s

Sam Aaron live coding an ambient electro set w/ Sonic Pi, https://www.youtube.com/watch?v=G1m0aX9Lpts

Live Coding Channel von Sam Aaron, https://www.livecoding.tv/samaaron/

Alexandre rANGEL 'bit crusher' Sonic Pi live coding, https://www.youtube.com/watch?v=7Yr-HGRikRg

Live coding dub techno in Sonic Pi von Jindřich Mynarz, https://www.youtube.com/watch?v=a1RxpJkvqpY

The Wood-Song: Ambient Live Coding Exercise with Sonic Pi, M.Butz, https://www.youtube.com/watch?v=3zGt-1JSfgA

Live Coding with Sonic Pi, M. Butz, https://www.youtube.com/watch?v=80Sw7G-4nno

Personal Live Coding Challenge #2, M. Butz, https://www.youtube.com/watch?v=WOaLgQ_p2S0

Toplap - Home of Live Coding, http://toplap.org/
