[< Back](../README.md)

# Calendar - User Guide

The Calendar feature in KeepWatching gives you a visual overview of when your shows air new episodes and when movies are released. You can see upcoming and recently aired content at a glance without leaving the app.

## Accessing the Calendar

The Calendar is available in two ways:

- **Home page shortcut**: A **View Calendar** button appears in both the TV Shows tab and the Movies tab on your Home dashboard, linking directly to the full Calendar page.
- **Direct navigation**: Navigate to `/calendar` from the main navigation menu.

## Views

The Calendar offers two display modes that you can toggle between at any time. Your preferred view is saved automatically and restored on your next visit.

![Watch History Screenshot](../images/calendar/calendar_header.png)

### Agenda View (List)

![Watch History Screenshot](../images/calendar/calendar_agenda_today.png)

The agenda view shows a scrollable, day-by-day list of content. Each day section lists the episodes and movies airing or releasing on that date, including the show or movie title, episode name (for TV), and a link to the relevant detail page.

This view is ideal for seeing everything in order at a glance, particularly on mobile devices.

### Grid View (Month Calendar)

![Watch History Screenshot](../images/calendar/calendar_calendar.png)

The grid view displays a traditional month calendar layout. Each day cell shows a count of episodes and movies airing that day. Clicking a day opens a detail panel listing each item for that date.

![Watch History Screenshot](../images/calendar/calendar_calendar_day.png)

Use the **previous** and **next** arrow buttons to navigate between months. When you navigate to a month outside the already-fetched date range, the calendar automatically fetches new data for that period.

## Date Range & Caching

By default the calendar loads content spanning 30 days in the past and 60 days into the future from today. When you navigate to a month outside that range, the app fetches the additional data automatically. Already-fetched data is cached for 5 minutes before being considered stale and refreshed.

## Content Shown

The calendar includes:

- **Episodes**: Upcoming and recently aired episodes from shows in your profile, grouped by air date
- **Movies**: Upcoming releases and recent releases from movies in your watchlist, grouped by release date

Each item links to its show or movie detail page so you can mark it watched or view more information.

## Tips

- Use the **Agenda** view as your day-to-day check on what aired recently
- Use the **Grid** view for planning ahead across a full month
- Combine the Calendar with the **Upcoming Episodes** and **Upcoming Releases** sections on the Home page for a complete picture of your content schedule
