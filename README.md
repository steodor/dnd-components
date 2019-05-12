### UNDER CONSTRUCTION
- there's currently nothing here. I wish to finish it this year (2019) but i make no promises.

# dnd-kanman
The Drag'n'Drop Kanban Manager - turns your DOM elements into a Kanban board and Manages essential user interaction. Works on desktop and mobile devices. It's opinionated because it's built with fairly large datasets and mobile performance in mind. Thus, optionally it can take over scrolling and make it "infinite" to cap the number of DOM elements being rendered at any given moment.

### Features:
- **smooth drag and drop**: optimized for fluency on big datasets, at the expense of memory.
- **nested, collapsible lists**: this is something i haven't found in any other Kanban UI library - tell me if i'm wrong.
- **drop-action docks**: docks (or drawers) which appear when starting a drag operation, where you can drop stuff to apply various operations, e.g. "Delete item". Docks can be bound to the board or to a list.

## Install
TODO: add `npm` install instructions here

## Components
- Board: container of Lists. Singleton (one board per page). Horizontal scroll only. Drop target for Lists.
- List: container of Items and/or other Lists. Vertical scroll only. Draggable. Drop target for Items and Lists.
- Item: final bit of information. Draggable.
- Dock: container of Drop targets which appears upon drag start. Can bind to the edge of a Board or List.
