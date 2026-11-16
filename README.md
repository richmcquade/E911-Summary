# E911 Summary

Interactive prototype of the E911 Queue's Medical category and data details pane, based on the supplied light-theme screenshots.

## Open the prototype

Download this repository and open `index.html` in a browser. No installation, build step, or internet connection is required. GitHub's file viewer displays the source; download the file to interact with it.

## Proposed behavior

- The prototype starts with **Medical selected** and the medical details pane open.
- Click **Medical** to unselect it, close the details pane, and restore the full AI Summary view.
- Click **Medical** again to select it and reopen the medical details pane.
- Click the **X**, immediately left of the existing popout box/arrow icon, to close the details pane and unselect Medical.
- Closing the details pane preserves all AI Summary sections, including the Medical summary.
- Closing with X returns keyboard focus to Medical. The button also exposes its selected and expanded states to assistive technology.

## Prototype scope

Only the Medical toggle and details close button are interactive. The popout icon and other queue controls are included for visual context. All displayed information is illustrative content reproduced from the supplied mockups; this prototype has no connection to live calls or medical data.

## Verification

The interaction checks cover deselection, reopening, closing with X, synchronized button state, and keyboard focus returning to Medical.
