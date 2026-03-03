README.md
Franklin for Supervisor – Email Integration Test

This repository contains a front-end prototype for testing an email integration workflow for the Franklin for Supervisor campaign website.

Overview

The goal of this project is to:

Capture a visitor’s email and message via a web form

Send that message to an external organization

Route the email through a configured email service/app

Test front-end behavior using HTML and CSS

This is a structural prototype focused on layout and integration logic, not final production styling.

Tech Stack

HTML5

CSS3

Email service integration (configured externally)

Project Structure
/index.html        → Main form layout
/styles.css        → Form styling
/assets/           → Optional images or static assets
Features

Responsive contact form layout

Visitor email capture

External recipient routing

Structured for easy backend or API hook-in

Intended Workflow

Visitor enters their name and email.

Visitor submits the form.

The configured email app/service sends:

A message to the external organization

(Optional) A confirmation copy

Status

Testing phase.
Front-end structure complete.
Integration configuration in progress.

Future Improvements

Backend validation

Spam protection (reCAPTCHA or honeypot)

Logging + email list storage

Multi-recipient routing

Error handling UI states

Notes

This repository is intended for campaign-specific testing and integration validation.
