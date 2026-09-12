# Privacy Policy — Whoop MCP Server (Personal Use)

This is a personal-use application that connects to the Whoop API on behalf of its
single owner/operator. It is not distributed to or used by any other end users.

## Data Collected

Via the Whoop API (with the account holder's OAuth consent), this app retrieves:

- Recovery metrics (HRV, resting heart rate, SpO2, skin temperature)
- Sleep data (stages, duration, efficiency)
- Strain and workout history
- Cycle/day summary data

## How Data Is Stored and Used

- Data is stored locally in a SQLite database controlled by the account owner
  (either on their own machine or on infrastructure they operate, such as a
  personal Railway deployment).
- Data is used only to display the account owner's own health metrics to
  themselves, through a personal AI assistant integration (Claude via MCP).
- Data is not sold, shared, or disclosed to any third party.
- Data is not used for advertising or analytics.

## Data Retention and Deletion

The account owner may delete all stored data at any time by removing the local
database file, and may revoke this app's access at any time from their Whoop
account settings.

## Contact

For questions about this app and its data handling, contact: ljykeith@gmail.com
