# Broken Kalvium Dashboard

This is the starter repo for the **Fix the Broken App - Your First Pull Request** activity.

You use the Kalvium dashboard every day on the platform. This repo contains a simplified version of that dashboard UI, but a few things are broken. Your job is to compare this app with the expected dashboard shown in the lesson, fix the issues, and open one clean Pull Request.

## What You Need To Do

Run the app, inspect the dashboard, and fix the visible problems so it matches the expected version again.

Work like a careful teammate:

- observe the UI before changing code
- find the smallest code change that explains each issue
- avoid redesigning the app
- avoid hardcoding values just to make one screen pass
- commit your fixes with a clear message
- open one Pull Request for the related dashboard fixes

## Run Locally

Install dependencies:

```bash
npm install
```

Start the dev server:

```bash
npm run dev
```

Open the local URL shown in your terminal, usually:

```text
http://localhost:5173
```

## Debugging Checklist

Before editing code, compare the broken dashboard with the expected dashboard from the lesson.

Check:

- the profile area
- the dashboard app cards
- notification badges
- the complete app list
- the overall layout

If something looks wrong, trace it back through the data, helper functions, and rendered components.

## Pull Request Expectations

Create a branch:

```bash
git checkout -b fix/dashboard-issues
```

After fixing and testing:

```bash
git add .
git commit -m "fix: resolve dashboard issues"
git push origin fix/dashboard-issues
```

Open one Pull Request. In the PR description, include:

- what was broken at a high level
- what you changed
- how to test the fixed dashboard

## What Not To Do

- Do not add new dashboard features.
- Do not rewrite the full app.
- Do not change unrelated files.
- Do not submit four separate PRs for these related fixes.
- Do not hardcode display text or counts when the data already exists.

## Completion Check

You are done when the dashboard matches the expected version from the lesson and your PR clearly explains the fix.
