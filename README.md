Ukupan broj linija za fajlove Calculator.java i Start.java je 214; ukupan broj linija koda ova dva fajla (LOC) je 153
Ciklomatska slozenost za fajl Calculator.java je 12; za Start.java je 3; Calculator.java-umereno kompleksan kod; Start.java-jednostavan kod

Start.java fajl je napisan programskim jezikom Java, sadrzi main metodu preko koje se vrsi komunikacija sa korisnikom

Upotrebom alata SonarLint detektovano je sledece:

Start.java is non -project file, only sintax errors are reported Java(16) [Ln 1, Col1];
Replace this use of System.out or System.err by a logger. [Ln 8, Col 3];
Replace this use of System.out or System.err by a logger. [Ln 19, Col 5];
Move this file to a named package. [Ln 1, Col 1];
Rename this local variable to match the regular expression '^[a-z][a-zA-Z0-9]*$'. [Ln 6, Col 10];

Fajl Calculator.java je napisan takodje programskim jezikom Java i moguce je izvrsavanje osnovnih matematickih operacija (sabiranje, oduzimanje, deljenje, mnozenje)
Upotrebom SonarLint alata detektovano je sledece:

Add a private constructor to hide the implicit public one. [Ln 4, Col 14];
Rename method "ToString" to prevent any misunderstanding/clash with method "toString" defined in superclass "java.lang.Object". [Ln 18, Col 30];
Move this file to a named package. [Ln 1, Col 1];
Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'. [Ln 18, Col 30];
Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'. [Ln 24, Col 26];
Immediately return this expression instead of assigning it to the temporary variable "textResult". [Ln 70, Col 29];
Rename this method name to match the regular expression '^[a-z][a-zA-Z0-9]*$'. [Ln 74, Col 25];
Remove this redundant jump. [Ln 183, Col 13];
