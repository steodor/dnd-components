# UNDER CONSTRUCTION, WIP, WTV
this is under construction, work in progress, whatever... - it's not on `npm` yet!

# dnd-kanman
The Drag'n'Drop Kanban Manager - turns your DOM elements into a Kanban board and Manages essential user interaction. Works on desktop and mobile devices. It is highly opinionated, because performance is paramount. Want more flexibility? Feel free to fork and make it more generic or why not, start a separate project based on this one.

### Features:
- **smooth drag and drop**: optimized for fluency on big datasets
- **nested, collapsible lists**: this is something currently missing from any other Kanban UI library out there
- **drop-action drawers**: docks which appear when starting a drag operation, where you can drop stuff to apply various operations, e.g. "Delete item"

## Install
TODO: add `npm` install instructions here

## Components
- Board: container of Lists. Singleton (one board per page). Scrolls horizontally. Drop target for Lists.
- List: container of Items and/or other Lists. Scrolls vertically. Draggable. Drop target for Items and Lists.
- Item: final bit of information. Draggable.
- Dock: container of Drop targets which appears upon drag start.
