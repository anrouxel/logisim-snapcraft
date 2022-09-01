# Logisim Snapcraft

[![🧪 Test snap can be built on x86_64](https://github.com/anrouxel/logisim-snapcraft/actions/workflows/snapcraft-test.yml/badge.svg)](https://github.com/anrouxel/logisim-snapcraft/actions/workflows/snapcraft-test.yml)

Empaquetage de Logisim pour Snapcraft

Logisim is a digital circuit simulator

This is an italian fork based on the original Logisim version.

**DOWNLOAD AND CHANGELOG :** https://logisim.altervista.org

**CONTACT US :** https://logisim.altervista.org/contacts.html

**PLUGINS :** https://logisim.altervista.org/plugins.html

**USER TUTORIALS :** https://logisim.altervista.org/userstutorial.php

**DEVS TUTORIALS :** https://logisim.altervista.org/developerstutorial.php

**Why you should use Logisim ITA :**
* No retro-compatibility problems with old .circ files
* A lot of new components and small changes
* Bug fixes and optimizations
* Constantly supported and listening to all your suggestions/reports

**Bugs :**

All the original Logisim's bugs we haven't fixed yet :

* Some random blue/red line caused by bad values refresh
* Some problem with high frequencies
* String attribute not calling attributechanged method while writing its value

Programmable Generator: trying to edit its values by clicking on "(click to edit)" is a bit buggy, use "Edit Contents" instead in menu by clicking with right mouse button

**Features we want to add :**

* Solve dirty points when rotating
* Add a new type of library
* Draw also in circuits
* Suggest us everything at logisimit@gmail.com

**Retro-compatibility :**

Due to a bug in the original Logisim, wide gates with 4 inputs had a bad pin positioning.
I fixed this problem but if you open an old file containing gates with those attributes, its inputs will be disconnected and a warning message will appear

**EXE and JAR downloads + microprocessor project :**

All in our website https://logisim.altervista.org

**How to compile & use :**

The project uses maven, from `Logisim/Logisim-Form` run `mvn package` or use your ide and import the directory as a maven project,
the output file is `target/Logisim-jar-with-dependencies.jar`

If you use ecplise, or a older version of Logisim:  
Watch our tutorials on "TUTORIAL" section of our [website](https://logisim.altervista.org/developerstutorial.php)

**Translation :**

New strings are translated really bad (Google Translate) because i just know Italian and English.

You can help me translating other languages or adding a new one, if you want so, contact me at logisimit@gmail.com

**Source code :**

* **Github (compilation) :** https://github.com/anrouxel/Logisim_snapcraft

* **Github (source) :** https://github.com/Logisim-Ita/Logisim
