---
author: Leo Traven
pubDatetime: 2026-02-25T18:22:00Z
modDatetime: 2026-02-25T18:22:00Z
title: Becoming a manager of agents
slug: becoming-a-manager-of-agents # seen in the url
featured: false
draft: false
tags:
  - ai
  - agents
description: Although being a developer, I find myself acting more and more like a manager.
---

<!-- Situation -> Complication -> Question -> Answer -->

Quick reference: [Deutsch](#deutsche-version)

### TL;DR:
- Software engineering once was about writing code manually
- Nowadays, agents can serve on behalf of software engineers
- The role of software engineers changes from manual building to managing agents, which drastically increases their leverage
- Strategy and quality gates are more important than ever
- You still have to understand what you build to make good decisions


### The end of manual syntax
When I pivoted to software engineering in 2022, I spent a lot of time learning Python.
The job was about writing code manually, line by line.
Sometimes, this involved searching for errors in the code for several hours.

Since then, AI agents gradually became more powerful.
They consist of generative AI models coupled with tools that enable them to interact with their environment.
Given the right context, they can work on their own in the digital space.
Based on instructions and work contexts, they choose tools to be executed.
For example, a tool might allow them to edit a file.
The AI model can say which file it wants to edit, which parts of the file it wants deleted and what it wants to be added.
This is especially helpful for coding, where you have repositories consisting of many files that each are full of code.
You typically store code in one file, and reference it in another one.
This way, you can use different areas of a repository to serve different purposes.

Understanding how code works can be hard.
This is especially the case if you did not write the code yourself.
In the beginning of 2025, I was surprised when an agent could solve a coding problem at first try.
Now, I'm disappointed when it can't.
In most cases, it is not only faster to let agents write code for you, but the quality is often higher than what I could have produced.

<!-- ### What do you even need developers for? -->

### The role of software engineers is shifting from manual building to managing agents

I find myself outsourcing more and more work to agents.
My focus is not on creating code anymore, but on reviewing it.
Essentially, the coding layer is abstracted away.
As it's easier and easier to produce code, the value of each unit of code diminishes.
If I want a hyper-personalized app just for myself, it's now easier than ever to get it.
If I realize that I am not satisfied with a solution to a coding problem, I just throw it away and start from scratch again.

As each developer has an increasingly big lever to make changes, it is crucial for teams to define common strategies.
This can contain architecture decisions, but also code quality standards and development methodologies.
As AI agents increase development speed enormously, the direction of development is more important than ever.
If you go into the wrong direction, speed does not help you.
To make sure I am on the right track, I find myself aligning with colleagues more and more often.

To control agents, it's all about setting the right guardrails.
If newly generated code does not pass the bar for security, it should be declined.
You can also build loops of agents controlling each other.
One agent can generate code, while the other one ensures its quality and security.
By closing these loops, developers can focus on giving strategic directions.

I find myself constantly evaluating agent outputs against the target architecture of the system I want to build.
To do so, I have to understand what my agents do and what this means for my system.
Then I have to refine.
As it turns out, software engineers are still programming.
The syntax has just changed to natural language.


<!-- - Skills are changing
- Software engineers are still coding - but in natural language
- Role of developers changes to project managers
- it's all about closing loops and managing context


What are caveats?
- If you do not know the direction, every street is correct???
- it's important to enforce quality gates -->

## Deutsche Version

### TL;DR:
- Software Engineering drehte sich früher darum, Code manuell zu schreiben
- Heute können Agenten im Auftrag von Software Engineers arbeiten
- Die Rolle von Software Engineers verschiebt sich vom manuellen Bauen hin zum Managen von Agenten, was ihren Hebel drastisch vergrößert
- Strategie und Quality Gates sind wichtiger denn je
- Du musst trotzdem verstehen, was du baust, um gute Entscheidungen zu treffen


### Das Ende der manuellen Syntax
Als ich 2022 in die Softwareentwicklung gewechselt bin, habe ich viel Zeit damit verbracht, Python zu lernen.
Der Job bestand darin, Code manuell zu schreiben, Zeile für Zeile.
Manchmal bedeutete das, stundenlang nach Fehlern im Code zu suchen.

Seitdem sind AI-Agenten nach und nach leistungsfähiger geworden.
Sie bestehen aus generativen AI-Modellen, gekoppelt mit Tools, die es ihnen erlauben, mit ihrer Umgebung zu interagieren.
Mit dem richtigen Kontext können sie eigenständig im digitalen Raum arbeiten.
Basierend auf Instruktionen und Arbeitskontexten wählen sie Tools aus, die ausgeführt werden sollen.
Zum Beispiel kann ein Tool es ihnen ermöglichen, eine Datei zu bearbeiten.
Das AI-Modell kann sagen, welche Datei es bearbeiten will, welche Teile es löschen will und was hinzugefügt werden soll.
Das ist besonders hilfreich beim Coden, wo du Repositories mit vielen Dateien hast, die jeweils voller Code sind.
Typischerweise speicherst du Code in einer Datei und referenzierst ihn in einer anderen.
So kannst du verschiedene Bereiche eines Repositories für verschiedene Zwecke nutzen.

Zu verstehen, wie Code funktioniert, kann schwierig sein.
Das gilt vor allem dann, wenn du den Code nicht selbst geschrieben hast.
Anfang 2025 war ich überrascht, wenn ein Agent ein Coding-Problem beim ersten Versuch lösen konnte.
Jetzt bin ich enttäuscht, wenn er es nicht kann.
In den meisten Fällen ist es nicht nur schneller, Agenten Code schreiben zu lassen, die Qualität ist oft auch höher als das, was ich selbst produziert hätte.

### Die Rolle von Software Engineers verschiebt sich vom manuellen Bauen zum Managen von Agenten

Ich finde mich dabei, immer mehr Arbeit an Agenten auszulagern.
Mein Fokus liegt nicht mehr darauf, Code zu erzeugen, sondern ihn zu reviewen.
Im Kern wird die Coding-Ebene abstrahiert.
Weil es immer einfacher wird, Code zu produzieren, sinkt der Wert jeder einzelnen Code-Einheit.
Wenn ich eine hyperpersonalisierte App nur für mich selbst will, ist es heute einfacher denn je, sie zu bekommen.
Wenn ich merke, dass ich mit einer Lösung für ein Coding-Problem nicht zufrieden bin, werfe ich sie einfach weg und starte nochmal von vorne.

Da jeder Developer einen immer größeren Hebel hat, Veränderungen vorzunehmen, ist es entscheidend, dass Teams gemeinsame Strategien definieren.
Das kann Architekturentscheidungen enthalten, aber auch Code-Qualitätsstandards und Entwicklungsmethoden.
Da AI-Agenten die Entwicklungsgeschwindigkeit enorm erhöhen, ist die Entwicklungsrichtung wichtiger denn je.
Wenn du in die falsche Richtung läufst, hilft dir Geschwindigkeit nicht.
Um sicherzugehen, dass ich auf dem richtigen Kurs bin, richte ich mich immer häufiger mit Kollegen ab.

Um Agenten zu steuern, geht es darum, die richtigen Guardrails zu setzen.
Wenn neu generierter Code die Sicherheitslatte nicht erfüllt, sollte er abgelehnt werden.
Du kannst auch Schleifen bauen, in denen Agenten sich gegenseitig kontrollieren.
Ein Agent kann Code generieren, während ein anderer seine Qualität und Sicherheit absichert.
Wenn du diese Schleifen schließt, können Entwickler sich darauf fokussieren, strategische Richtung zu geben.

Ich evaluiere Agenten-Outputs ständig gegen die Zielarchitektur des Systems, das ich bauen will.
Dafür muss ich verstehen, was meine Agenten tun und was das für mein System bedeutet.
Dann muss ich verfeinern.
Am Ende zeigt sich: Software Engineers programmieren immer noch.
Nur die Syntax hat sich zu natürlicher Sprache verschoben.

