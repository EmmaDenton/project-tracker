# project-tracker

### Task 1: HTML Build

1. Create a header/hero area that welcomes users to the application and displays the current time and date using Day.js. The current time and date should be updated every second with `setInterval()`. The data should be formatted with the abbreviated month, day, full year, and time (e.g. `Jun 30, 2022 at 08:37:48 am`).

2. Create a Bootstrap card component explaining the instructions of how to use the app and a button to open a [Bootstrap modal dialog](https://getbootstrap.com/docs/5.1/components/modal/).

3. The modal should contain a form asking users to fill in the following data:

    * The name of the project.

    * The type of project (use a `<select>` drop-down).

    * The date the project is due (use the `date` input type).

    * Optional: Use the jQuery UI datepicker instead of `date` input type.