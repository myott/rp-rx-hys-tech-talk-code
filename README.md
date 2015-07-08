# rp-rx-hys-tech-talk-code

## Local Build
To build locally, run:

  $ ./gradlew clean asciidoctor

## Generated Presentation
The outputs will be located at:

  build/asciidoc/revealjs

## Using IntelliJ
If you want to use IntelliJ, run:

  $ ./gradlew idea
  
To generate the IntelliJ specific files.

## Auto-recompile Asciidoctor files
To have Gradle automatically recompile the asciidoctor documents, run:

  $ ./gradlew clean asciidoctor watch
  
This utilizes the https://github.com/bluepapa32/gradle-watch-plugin[gradle-watch-plugin] to watch files for changes.
