# morning-brief : AI-powered daily standup and job application tracker using Gmail and Gemini API

Summary:
An agentic web app that reads your Gmail, generates a daily standup, and tracks your job applications — all in one click.
What it does
Every time you hit Run, the app:

Reads your Gmail inbox from the last 24 hours via OAuth
Sends the email data to Gemini 2.5 Flash for synthesis
Generates a standup — what you did yesterday, blockers, today's focus
Classifies action items by priority (HIGH, MEDIUM, LOW)
Flags urgent emails that need attention today
Tracks job applications with status (applied, reviewing, interview, rejected, opportunity)
Saves your application pipeline to Google Sheets automatically

Live app
https://akshdeep0611.github.io/morning-brief/
