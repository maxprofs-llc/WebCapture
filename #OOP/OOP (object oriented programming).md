# OOP (object oriented programming)

_Captured: 2015-09-23 at 12:38 from [www.itwissen.info](http://www.itwissen.info/definition/lexikon/Objektorientierte-Programmierung-OOP-object-oriented-programming.html)_

Die objektorientierte Programmierung (OOP) ist eine [Methode](http://www.itwissen.info/definition/lexikon/Methode-method.html) zur Modularisierung von [Programmen](http://www.itwissen.info/definition/lexikon/Programm-program.html), die sich stark von der klassischen [prozeduralen Programmierung](http://www.itwissen.info/definition/lexikon/Prozedurale-Programmierung-procedural-programming.html) unterscheidet. Objektorientierte [Software](http://www.itwissen.info/definition/lexikon/Software-SW-software.html) ist, wenn sie gut entworfen wurde, leichter zu warten und zu erweitern als prozedurale. Zudem vereinfacht sie durch die strenge Modularisierung Unit-Tests und Wiederverwendung von Softwareteilen. Sie folgt dem [Programmierparadigma](http://www.itwissen.info/definition/lexikon/Programmierparadigma-programming-paradigma.html) der [imperativen Programmierung](http://www.itwissen.info/definition/lexikon/Imperative-Programmierung-imperative-programming.html).

Bei der objektorientierten Programmierung werden Programme in Einheiten unterteilt, die [Objekte](http://www.itwissen.info/definition/lexikon/Objekt-O-object.html) genannt werden. Jedes Objekt besitzt einen Zustand, der durch dessen Eigenschaften (Objektattribute) beschrieben wird. Nur die im Objekt selbst vorhandenen Funktionen (Methoden genannt), konnen dessen [Daten](http://www.itwissen.info/definition/lexikon/Daten-data.html) manipulieren und so den Zustand verandern. Objekte konnen anderen Objekten Botschaften senden (indem sie deren Methoden aufrufen) und sie damit auffordern, ihren Zustand zu andern. Letztendlich bleibt es aber dem Objekt selbst uberlassen, ob es der Aufforderung nachkommt. Somit befindet sich das Objekt immer in einem wohldefinierten, selbstkontrollierten Zustand.

Man fasst in der OOP-Programmierung also Daten und Funktionen zu Objekten zusammen. Diese Objekte konnen auf vielfaltige Weise miteinander in [Verbindung](http://www.itwissen.info/definition/lexikon/Verbindung-connection.html) stehen, indem sie gegenseitig ihre Methoden aufrufen oder ein Objekt andere Objekte enthalt. So bilden die Objekte einer Software ein sehr flexibles Gesamtsystem.

Jedes Objekt gehort zu einer [Klasse](http://www.itwissen.info/definition/lexikon/Klasse-class.html). Klassen werden auch oft als Bauplane fur Objekte beschrieben, weil sie definieren welche [Attribute](http://www.itwissen.info/definition/lexikon/Attribut-attribute.html) und Methoden die dazugehorigen Objekte besitzen. Jedes Objekt ist eine [Instanz](http://www.itwissen.info/definition/lexikon/Instanz-entity.html) seiner Klasse, man sagt auch: Das Objekt "o" instanziiert die Klasse "k". Von einer Klasse kann es beliebig viele Objekte geben, deren Eigenschaften sich unterscheiden konnen aber nicht mussen. Ein [Warenwirtschaftssystem](http://www.itwissen.info/definition/lexikon/Warenwirtschaftssystem-ERP-system-WWS.html) beispielsweise kennt nur eine Klasse Artikel, aber viele Artikelobjekte.

Objektorientierte Programme erfullen verschiedene wichtige Kriterien, die die Entwicklung vereinfachen, beschleunigen und gleichzeitig die Qualitat verbessern konnen:

  * Datenkapselung: Die Daten eines Objekts konnen nicht unkontrolliert von außen verandert werden, letztendlich entscheidet immer das Objekt selbst uber Änderungen seines Zustands. 
  * Austauschbarkeit: Objekte sind [Abstraktionen](http://www.itwissen.info/definition/lexikon/Abstraktion-abstraction.html) realer Entitaten und Akteure, die ihre tatsachliche [Implementierung](http://www.itwissen.info/definition/lexikon/Implementierung-implementation.html) vor der Außenwelt verbergen und dadurch austauschbar werden. 
  * Vererbung: Eigenschaften und Funktionen eines Objekts konnen an andere Objekte weitergegeben und von diesen ubernommen, verandert oder uberschrieben werden. 
  * Polymorphie unterstutzt die Austauschbarkeit von Objekten, denn die gleiche [Nachricht](http://www.itwissen.info/definition/lexikon/message-Nachricht-MSG.html) kann an unterschiedliche Objekte gesendet werden und dementsprechend unterschiedliche Aktionen bei diesen bewirken. 

Programmiersprachen fur objektorientierte Programmierung.

Nicht jede [Programmiersprache](http://www.itwissen.info/definition/lexikon/Programmiersprache-PL-programming-language.html) unterstutzt die objektorientierte Programmierung. C und [Pascal](http://www.itwissen.info/definition/lexikon/Pascal.html) sind beispielsweise rein prozedural. Andere [Sprachen](http://www.itwissen.info/definition/lexikon/Sprache-speech.html) wie [C++](http://www.itwissen.info/definition/lexikon/C-plus-plus.html) oder [Object Pascal](http://www.itwissen.info/definition/lexikon/Object-Pascal.html) erlauben [OOP](http://www.itwissen.info/definition/lexikon/occupant-out-of-position-OOP.html), erzwingen sie aber nicht. Die daraus resultierenden Programme konnen eine Mischung aus verschiedenen Paradigmen sein. Das gleiche gilt fur Sprachen wie [Hypertext Preprocessor](http://www.itwissen.info/definition/lexikon/hypertext-preprocessor-PHP.html) (PHP) oder [Perl](http://www.itwissen.info/definition/lexikon/practical-extraction-and-report-language-PERL.html), die durch [Erweiterungen](http://www.itwissen.info/definition/lexikon/Erweiterung-expansion.html) OOP-fahig gemacht werden konnen. Weitere wie [Eiffel](http://www.itwissen.info/definition/lexikon/Eiffel.html), [Smalltalk](http://www.itwissen.info/definition/lexikon/Smalltalk.html), [Java](http://www.itwissen.info/definition/lexikon/Java.html) oder [C#](http://www.itwissen.info/definition/lexikon/C-sharp.html) sind rein objektorientiert.

Neben der eigentlichen objektorientierten Programmierung haben sich auch objektorientierte Verfahren zur [objektorientierten Analyse](http://www.itwissen.info/definition/lexikon/Objektorientierte-Analyse-OOA-object-oriented-analysis.html) (OOA) und zum [objektorientierten Design](http://www.itwissen.info/definition/lexikon/Objektorientiertes-Design-OOD-object-oriented-design.html) (OOD) von Softwaresystemen etabliert. Dabei hat sich die [Unified Modelling Language](http://www.itwissen.info/definition/lexikon/unified-modelling-language-UML.html) (UML) als allgemein anerkannte [Notation](http://www.itwissen.info/definition/lexikon/Notation-notation.html) fur diese Verfahren durchgesetzt. Entsprechende Softwaretools, die teilweise in Entwicklungsumgebungen (IDEs) integriert werden, erlauben die Generierung von Software aus grafisch entworfenen Systemen oder dokumentieren umgekehrt fertige Systeme in UML-Notation.

Ein in der Praxis immer wiederkehrendes Problem mit vielen Losungsansatzen ist die Verbindung von [relationalen Datenbanken](http://www.itwissen.info/definition/lexikon/relational-database-management-system-RDBMS-Relationales-Datenbank-Managementsystem.html) (RDBMS) und objektorientierter Software. Das Object Relational [Mapping](http://www.itwissen.info/definition/lexikon/mapping-Abbildung.html) (ORM) fuhrt eine Umsetzung relationaler Strukturen in Objekte und umgekehrt durch. Alternativ konnen auch objektrelationale oder [objektorientierte Datenbanken](http://www.itwissen.info/definition/lexikon/Objektorientierte-Datenbank-ODB-object-oriented-database.html) benutzt werden, deren Verbreitung allerdings nicht sehr groß ist.

[zuruck](javascript: history.go\(-1\);)