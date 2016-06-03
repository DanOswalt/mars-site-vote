1. Rearrange file structure a little bit to make a little more sense
2. Deleted unnecessary files
3. Add jQuery cdn
4. Change most DOM manipulation to jQuery selectors and click handlers
5. Removed 'didReset' logic, it didn't seem to do anything
6. Used map and forEach in a few places
7. We noticed that reseting the data did not redraw the chart, so we added that functionality
8. Noticed some redundant code, such as a click handler in two places
