
## User-requested updates (2026-10-21)
- Removed the bulk "28-08-2026 Rates सभी Blocks में Feed करें" action and its overwrite-all-blocks function.
- Disabled recurring live-price refresh and periodic server-state pulls that could redraw/overwrite unsaved data. Dashboard data is refreshed after Save Changes; saved changes are pushed to the server.
- Date fields now allow selecting a later date, so the same rates can be saved again for another date as a separate dated snapshot.
- Added Block Data Transfer controls for both the 23-item PMC table and the 18-item Additional table. Transfer copies the selected table into a chosen existing tehsil/block for the selected date.
- Added a "Fit table to one page" option to both PDF export controls, using compact text and cell spacing.
