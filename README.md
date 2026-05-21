# IT3100E Object-Oriented Programming Coursework

This repository contains Java coursework and lab exercises for IT3100E. The main
project is an AIMS media store application built with object-oriented design,
collections, inheritance, interfaces, comparators, and Java GUI exercises.

## Main Project: AIMS Media Store

The AIMS project models a small media store with:

- Media domain classes: `Book`, `DigitalVideoDisc`, `CompactDisc`, `Track`
- Shared abstraction through `Media`, `Disc`, and `Playable`
- Store and cart management
- Sorting and comparison by title/cost
- Console interaction flow
- JavaFX/Swing screen experiments
- UML/use-case/class diagram artifacts

Key source path:

```text
AimsProject/src/hust/soict/dsai/aims/
```

## Repository Structure

```text
AimsProject/
  src/                 # Main Java source code
  Design/              # Class diagram files
  Requirement/         # Use-case diagram files
  Reading Assignment/  # Course reading answers
GUIProject/            # JavaFX and Swing exercises
OtherProjects/         # Lab exercises
```

## How To Run

Compile and run from the repository root with a JDK installed:

```bash
javac -d out AimsProject/src/module-info.java AimsProject/src/hust/soict/dsai/aims/**/*.java
java -p out -m AimsProject/hust.soict.dsai.aims.Aims
```

Depending on your shell, you may need to compile the source tree using your IDE
or expand the glob manually.

## My Contribution

- Implemented the AIMS object model and cart/store workflows.
- Practiced inheritance, interfaces, comparators, and Java package structure.
- Added GUI exercises with JavaFX and Swing.
- Maintained the course artifacts and diagrams for review.

## Notes

Build outputs such as `.class` files and `bin/` folders are intentionally not
tracked. This keeps the repository readable as source code rather than an IDE
export.

