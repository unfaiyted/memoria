# FIX:
- FIXED: add dropdown button to override language detection.
- FIXED: hide ctrl+v when in mobile
- FIXED: auto focus on code editor
- FIXED: make view password button
- FIXED: add password hidden on view page
- FIXED: unknown languages cause paste viewer to stop working. (sql) "Loading content"
- FIXED: expand paste input
- FIXED: password, press enter should submit the form
- FIXED: add debounce to copy button on view page
- FIXED: hide second copy button on paste viewer, shown when entering code mode
- FIXED: move copy more to the left on larger screens. looks good on mobile
- FIXED: hide the delete buttons when the bar is closed.
- FIXED: no border at all on the new pastes makes the inputs too close I think.
- FIXED: copy to clipboard on private access page not hiding on code 
- FIXED: should have some more lines on the code editor. feels weird to use clicking the blank area could also add focus instead? 
- FIXED: Not loading when going to different pastes now. Just loads one and stays on that one

- side bar popups scroll down with large pages. need to get them fixed on the sidebar position. 
- (pasteViewer) improve code block display when paste was in text mode
- figure out how to get the tooltip for the private paste to not load in like that. maybe 0 opacity initialy or something


# Feature Add:
- ADDED: delete private pastes from list, soft delete from local storage
- ADDED: add icons based on language that is pasted
- ADDED: share button that also has the ability to delete private local pastes
- ADDED: change count down circle color to yellow/red as it gets lower.
- ADDED: Make it so you know which of the pastes is currently active from the sidebar

- finish short url api call integration
- Pretty drop down for the actual time of when it expires
- add settings button working? what kind of settings should I add?

