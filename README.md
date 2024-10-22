# QuickSell Frontend Assignment

An interactive Kanban board application built using React JS and SCSS. The board dynamically adjusts based on user grouping preferences. It interacts with the provided API from [Quicksell](https://api.quicksell.co/v1/internal/frontend-assignment).

## Features

- **Conditional Rendering**: Components are rendered based on the state and user preferences.
- **Grouping**:
  - **By Status**: Tickets are grouped based on their current status.
  - **By User**: Tickets are arranged according to the assigned user.
  - **By Priority**: Tickets are grouped based on their priority level.
- **Sorting**:
  - **Priority**: Tickets are arranged in descending order of priority.
  - **Title**: Tickets are sorted in ascending order based on their title.
- **User's View State Persistence**: The application saves the user's view state, even after a page reload.
- **Dynamic Data**: Fetches and displays data from the Quicksell API.
- **Custom Spinner**: An engaging spinner for better user experience during data fetching or other waiting times.
- **Available User Indicator**: Displays which users are currently available.


## Tech Stack

- **JavaScript**
- **React JS**
- **SCSS (CSS Preprocessor)**


