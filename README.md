# Weekly Schedule App

This repository contains the code for a weekly schedule app developed during School of Code - Bootcamp 14. 
The app allows users to view and manage weekly topics, workshops, recordings, and additional resources.

## Components

### App.js

The `App` component serves as the main entry point for the application. It renders the header, weekly topic bar, calendar, and footer components. 
It also manages the state of the `dateStart` variable using the `useState` hook.

### HeaderLogo.js

The `HeaderLogo` component displays the application logo and title.

### WeeklyTopicBar.js

The `WeeklyTopicBar` component displays the weekly topics based on the selected week in the calendar. 
It filters the data array to include only items that occur in the current week.

### Calendar.js

The `Calendar` component renders a calendar using the `FullCalendar` library. 
It displays pre-made events from the `data.js` file and allows users to select a week. 
It also includes a button in the day header cell to display additional resources.

### Modal.js

The `Modal` component is a pop-up modal that displays additional resources when the user clicks the resources button in the calendar.

### Footer.js

The `Footer` component displays social media icons and a mail icon for the School of Code.

