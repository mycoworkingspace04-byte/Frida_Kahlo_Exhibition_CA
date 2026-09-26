# Frida_Kahlo_Exhibition_CA — Audio Tour Painting List

## Overview
A Python exercise simulating real prep work for a museum audio tour: building a master
list that pairs each painting in a Frida Kahlo retrospective with its date and a unique
tour stop number.

## What it does
- Stores each painting's title and the year it was painted as two separate lists
- Combines them into paired records using `zip()`
- Adds late-arriving paintings to the collection with `.append()`
- Generates a sequential tour ID for every painting using `len()` and `range()`,
  so the numbering works no matter how many paintings end up in the show
- Builds one final master list combining each painting's info with its tour ID

## Skills demonstrated
- Python lists, tuples, and list methods (`.append()`)
- `zip()` and `list()` for combining separate data sources into one structure
- `len()` and `range()` for writing code that adapts to the data's size

## Example output
