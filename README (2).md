# HTU Club Events

A website that showcases student club events at Al Hussein Technical University (HTU) and gives clubs and the admin one place to manage them.

## Overview

HTU Club Events brings every student club activity into a single site. Students browse upcoming and past events, explore each club's profile and see photos from the day. Club representatives submit and track their own club's events. The admin reviews submissions, keeps the full record of activities and exports it in the same Excel layout the clubs already use.

The site follows HTU's visual identity, works in English and Arabic (with a right-to-left layout), and has light and dark modes. It is built as a single HTML file and runs in any modern browser on desktop or phone.

The site has three views:

- Student view: the public site. Only events approved by the admin appear here.
- Club view: a dashboard for one club's representative, limited to that club's events.
- Admin view: full access to every event, the review queue, and the import and export tools.

The current version is a demo. A switch at the top of the page changes between the three views, and changes are saved in the browser. Sign-in by email for the admin and each club is planned for the next stage.

## Key Features

### For students

- Home page with a "Next up" slider of upcoming events and a live countdown, which moves on its own or by arrows, dots and swipe.
- A summary of the year's activity: events held, clubs taking part, student initiatives, and the average number of events per month.
- Upcoming events as ticket-style cards that can be filtered by club.
- A past events archive grouped by semester, with search and club filters.
- Event pages showing the date, time, place, organising club or clubs, description, and a photo gallery with a full-screen viewer.
- A Clubs and student initiatives directory with each club's logo and English name: 24 clubs and 4 student initiatives.
- Club profile pages showing the club's events this year, upcoming and completed events, its collaborations, and the clubs it has worked with.
- A Collaborations tab for events run jointly by two or more clubs, such as Art Club and Chess Club. Joint events appear on every partner club's profile.

### For club representatives

- A "My club" dashboard with the club's live events, events waiting for approval, events returned by the admin, and missing post-event reports.
- A "Needs your attention" list showing returned events with the admin's note, and past events still missing a report.
- An add event form with the club name filled in and locked to the representative's own club, plus an optional partner club for collaborations.
- Fields matching the activities sheet: club, activity, place, start and end dates, start and end times, status, actual attendance, notes, activity permit, post-event report and photos.
- New events go to the admin for approval before students can see them. Returned events can be fixed and sent again.
- A Club profile tab showing the club's public page exactly as students see it.
- Export of the club's own events to Excel.

### For the admin

- An admin dashboard with a review queue. Each submission can be approved, or returned to the club with a short note explaining what to change.
- An All events table with every event from every club, with search, filters by club, status and year, and sortable columns.
- Adding, editing and deleting any event, and managing photos, permits and reports.
- Import of activities sheets in .xlsx or .csv format. Both the monthly tracking layout and the single-date layout are read, club names are matched to the official list, and events already on the site are skipped.
- Export to Excel in the activities-sheet layout: 12 columns (#, Club, Activity, Place, Start Date, End Date, Time, Status, Permit File, Report, Actual Att., Notes), month heading rows with activity counts, dropdown lists, and filters.
- Notes and permit file names that only the admin and the club can see.

### Across the site

- HTU look and feel: the HTU logo, red and navy colours, and each club's own logo and colour.
- English and Arabic, with a full right-to-left layout in Arabic.
- Light and dark modes with an animated sun and moon switch.
- Animated page transitions for each section.
- Layouts that adapt to phones, tablets and desktops.

## Objectives

- Give students one clear place to discover what is happening on campus and look back at what clubs have done.
- Give every club an easy, consistent way to submit its events and keep its permits, reports and attendance up to date.
- Let the admin review every event before it is published, so only confirmed activities reach students.
- Replace scattered spreadsheets with one source, while staying compatible with the Excel sheets already in use.
- Make club activity measurable: events per month and per year, activity per club, collaborations, attendance, and report completion.
- Encourage clubs to work together by making joint events visible on every partner club's profile.
- Present HTU student life in a way that matches the university's identity and works in both Arabic and English, on any device.
