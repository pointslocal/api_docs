# /api/v1/events

##### Request Parameters
- guid **[ string ]** - Event date's GUID.  This is a reference to an individual recursion's GUID, not the overall event
- start **[ string ]** - Event start date
- end **[ string ]** - Event end date.  Completes start <-> end range.
- date **[ string ]** - Event's date

##### Response Parameters
- title **[ string ]** - Event's title

## /api/v1/events/[:id]
Requests a specific event