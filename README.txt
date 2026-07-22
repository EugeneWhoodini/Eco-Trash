ECO TRASH WEBSITE — MOBILE OVERFLOW & IMAGE FIX

UPLOAD WITHOUT DELETING PREVIOUS FILES
1. Extract this ZIP.
2. Upload the public folder, vercel.json and README.txt into the existing GitHub repository.
3. Commit the files and allow Vercel to redeploy.

You do not need to delete old files. The new public/index.html references the current generated assets.

THIS VERSION INCLUDES
- Horizontal overflow is contained across the complete mobile page.
- Users can no longer swipe sideways into a blank white area.
- The mobile hero uses one full-width 4:5 image frame.
- The compressed secondary image is forcibly removed on mobile.
- The main photo uses object-fit cover so it keeps its proportions without stretching.
- The mobile status line can wrap safely without pushing the page wider.
- All phone, email and quote actions remain unchanged.

Repository root must contain:
public/
vercel.json
README.txt