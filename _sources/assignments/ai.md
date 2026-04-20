# In-Class Task: AI-Assisted Rapid Web App Development

## Topic: Stock Watchlist / Portfolio Web App

In this in-class task, you will use AI tools to rapidly build a usable web app about stocks.

Examples of AI tools include ChatGPT, Gemini, Claude, Copilot, Codex, and similar tools. You may use any AI tools you want.

The goal of this task is to see how much you can accomplish in class by combining your own web development skills with AI-assisted coding, debugging, design, and problem solving.

Your app must use **live stock data from a real external web service**.

## Main Goal

Build a web app that allows a user to:

- view live stock prices
- search or select stocks
- create and manage a personal watchlist or portfolio

This does **not** need to be a full commercial product. The goal is to create a working and usable prototype in class.

## Stock Data Requirement

Your app must use live data from a real stock data web service or API.

- You may choose **any** stock data service
- You are responsible for finding and integrating the service
- The data must be fetched from an external source during app usage
- You may not use only hard-coded local stock data

As one possible starting point, you may explore public API collections such as:

- <https://github.com/public-apis/public-apis>

You are **not limited** to that repository. You may use any real stock data service that works for your app.

## Required Features

Your app must include the following features.

### 1. Live Stock Data

The app must fetch live stock information from a real external service.

### 2. Stock Search or Selection

The user must be able to choose one or more stocks.

Examples:

- search by ticker symbol
- choose from a preset list
- click a stock from a watchlist

### 3. Current Stock Information

The app must display useful current stock information.

Examples:

- ticker symbol
- company name
- current price
- price change
- percent change
- last updated time

### 4. Watchlist or Portfolio

The user must be able to create a personal stock list.

You may implement either:

- a **watchlist**, where the user saves stocks to monitor

or

- a **portfolio**, where the user stores stocks plus additional information such as number of shares or buy price

### 5. Usable Interface

The app should be clear and usable.

It does not need to be perfect, but the layout should make sense and the main features should be easy to find and use.

## AI Usage

You are encouraged to use AI tools heavily during this task.

You may use AI tools for:

- planning
- code generation
- debugging
- styling
- API integration
- refactoring
- improving UI design

However, you are still responsible for:

- understanding your code
- testing your app
- fixing errors
- making the final product work

## Deployment Requirement

Your final app must be deployed to **GitHub Pages**.

Make sure your deployed app is accessible by URL and works correctly in the browser.

If your app has deployment limitations due to API restrictions, CORS issues, or key exposure concerns, clearly explain that in your development note. However, you should still make a strong effort to produce a working deployed version.

## Suggested Workflow

A good development order is:

1. Build a simple UI
2. Connect to one stock API
3. Display one working stock example
4. Add search or stock selection
5. Add watchlist or portfolio features
6. Deploy to GitHub Pages
7. Improve layout, styling, and error handling

## Optional Extra Features

If you finish early, you may add more features such as:

- portfolio total value
- gain/loss calculation
- stock price chart
- local storage
- refresh button
- loading state
- error messages
- dark mode
- responsive design
- favorite stocks

## Rules

- You may use any AI tools
- You may use plain HTML/CSS/JavaScript or a framework
- You may use any real stock data web service
- Your app must be a web app
- Your app must use live external stock data
- Your final app must be deployed to GitHub Pages
- Most of the work should be completed during class time

## Deliverables

Submit the following:

### 1. Source Code

Your full project code in GitHub.

### 2. GitHub Pages Link

A working deployed link to your app on GitHub Pages.

### 3. Short Development Note

Include a short note that lists:

- which AI tools you used
- which stock data service or API you used
- which features are working
- which features are incomplete
- any deployment limitations or API issues you encountered

## Grading Focus

This task will be evaluated mainly based on:

### Functionality

Does the app work and fetch live stock data correctly?

### Completion

How much of the required functionality is finished?

### Usability

Is the app reasonably clear and usable?

### Technical Integration

Did you successfully connect to and use a real external stock data service?

### Effective AI-Assisted Development

Did you use AI tools effectively to build a usable app quickly?

## Notes

- Some APIs may require an API key
- Some APIs may have rate limits
- Some APIs may be harder to use in browser-only apps
- Some APIs may fail, so be ready to adapt
- Part of this task is solving real integration problems with the help of AI tools

## Summary

By the end of class, your app should:

- fetch live stock data
- allow users to view one or more stocks
- include a watchlist or simple portfolio
- be deployed to GitHub Pages
- demonstrate how well you can build a usable app with AI-assisted rapid development
