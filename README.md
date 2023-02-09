```text
$ scala-cli doc .
Compiling project (Scala 3.3.0-RC2, JVM)
Compiled project (Scala 3.3.0-RC2, JVM)
-- Error: memoize.scala:26:10 --------------------------------------------------
26 |            else
   |          ^
   |          an identifier expected, but $XMLSTART$< found
-- Error: memoize.scala:32:26 --------------------------------------------------
32 |        List(cacheVal, newFib)
   |                          ^
   |                          Not found: type MacroAnnotation
2 errors found
Following generated file paths might not be compatible with Jekyll:
_empty_/Test
_empty_/Bar
_empty_/memoize
If using GitHub Pages consider adding a ".nojekyll" file.
[error]  Scaladoc generation failed (exit code: 1)
```

Actual command run by Scala CLI under-the-hood:
```text
$COURSIER_ARCHIVE_CACHE/https/github.com/AdoptOpenJDK/openjdk11-binaries/releases/download/jdk-11.0.9.1%252B1/OpenJDK11U-jdk_x64_mac_hotspot_11.0.9.1_1.tar.gz/jdk-11.0.9.1+1/Contents/Home/bin/java
-cp
$COURSIER_CACHE/https/repo1.maven.org/maven2/org/scala-lang/scaladoc_3/3.3.0-RC2/scaladoc_3-3.3.0-RC2.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/scala-lang/scala3-compiler_3/3.3.0-RC2/scala3-compiler_3-3.3.0-RC2.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/scala-lang/scala3-tasty-inspector_3/3.3.0-RC2/scala3-tasty-inspector_3-3.3.0-RC2.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/vladsch/flexmark/flexmark/0.42.12/flexmark-0.42.12.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/vladsch/flexmark/flexmark-html-parser/0.42.12/flexmark-html-parser-0.42.12.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/vladsch/flexmark/flexmark-ext-anchorlink/0.42.12/flexmark-ext-anchorlink-0.42.12.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/vladsch/flexmark/flexmark-ext-autolink/0.42.12/flexmark-ext-autolink-0.42.12.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/vladsch/flexmark/flexmark-ext-emoji/0.42.12/flexmark-ext-emoji-0.42.12.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/vladsch/flexmark/flexmark-ext-gfm-strikethrough/0.42.12/flexmark-ext-gfm-strikethrough-0.42.12.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/vladsch/flexmark/flexmark-ext-gfm-tables/0.42.12/flexmark-ext-gfm-tables-0.42.12.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/vladsch/flexmark/flexmark-ext-gfm-tasklist/0.42.12/flexmark-ext-gfm-tasklist-0.42.12.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/vladsch/flexmark/flexmark-ext-wikilink/0.42.12/flexmark-ext-wikilink-0.42.12.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/vladsch/flexmark/flexmark-ext-yaml-front-matter/0.42.12/flexmark-ext-yaml-front-matter-0.42.12.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/nl/big-o/liqp/0.8.2/liqp-0.8.2.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/jsoup/jsoup/1.14.3/jsoup-1.14.3.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/fasterxml/jackson/dataformat/jackson-dataformat-yaml/2.13.3/jackson-dataformat-yaml-2.13.3.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/scala-lang/scala3-interfaces/3.3.0-RC2/scala3-interfaces-3.3.0-RC2.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/scala-lang/scala3-library_3/3.3.0-RC2/scala3-library_3-3.3.0-RC2.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/scala-lang/tasty-core_3/3.3.0-RC2/tasty-core_3-3.3.0-RC2.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/scala-lang/modules/scala-asm/9.4.0-scala-1/scala-asm-9.4.0-scala-1.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/scala-sbt/compiler-interface/1.3.5/compiler-interface-1.3.5.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/jline/jline-reader/3.19.0/jline-reader-3.19.0.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/jline/jline-terminal/3.19.0/jline-terminal-3.19.0.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/jline/jline-terminal-jna/3.19.0/jline-terminal-jna-3.19.0.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/vladsch/flexmark/flexmark-util/0.42.12/flexmark-util-0.42.12.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/vladsch/flexmark/flexmark-formatter/0.42.12/flexmark-formatter-0.42.12.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/nibor/autolink/autolink/0.6.0/autolink-0.6.0.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/vladsch/flexmark/flexmark-jira-converter/0.42.12/flexmark-jira-converter-0.42.12.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/antlr/antlr4-runtime/4.7.2/antlr4-runtime-4.7.2.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/fasterxml/jackson/core/jackson-annotations/2.13.3/jackson-annotations-2.13.3.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/fasterxml/jackson/core/jackson-core/2.13.3/jackson-core-2.13.3.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/fasterxml/jackson/core/jackson-databind/2.13.3/jackson-databind-2.13.3.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/fasterxml/jackson/datatype/jackson-datatype-jsr310/2.12.1/jackson-datatype-jsr310-2.12.1.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/ua/co/k/strftime4j/1.0.5/strftime4j-1.0.5.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/yaml/snakeyaml/1.30/snakeyaml-1.30.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/scala-lang/scala-library/2.13.10/scala-library-2.13.10.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/google/protobuf/protobuf-java/3.7.0/protobuf-java-3.7.0.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/scala-sbt/util-interface/1.3.0/util-interface-1.3.0.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/net/java/dev/jna/jna/5.3.1/jna-5.3.1.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/vladsch/flexmark/flexmark-ext-tables/0.42.12/flexmark-ext-tables-0.42.12.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/vladsch/flexmark/flexmark-ext-ins/0.42.12/flexmark-ext-ins-0.42.12.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/com/vladsch/flexmark/flexmark-ext-superscript/0.42.12/flexmark-ext-superscript-0.42.12.jar
dotty.tools.scaladoc.Main
-classpath
./.scala-build/project_e372671733/classes/main:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/scala-lang/scala3-library_3/3.3.0-RC2/scala3-library_3-3.3.0-RC2.jar:$COURSIER_CACHE/https/repo1.maven.org/maven2/org/scala-lang/scala-library/2.13.10/scala-library-2.13.10.jar
-d
./.scala-build/project_e372671733/classes/main-doc
-sourceroot
.
-release
11
-snippet-compiler:compile
-Ygenerate-inkuire
-external-mappings:.*scala.*::scaladoc3::https://scala-lang.org/api/3.x/,.*java.*::javadoc::https://docs.oracle.com/javase/8/docs/api/
-author
-groups
./.scala-build/project_e372671733/classes/main
```