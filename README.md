# Big Cat Newspaper Workflow

A personal Calibre plugin for automating newspaper processing, PDF delivery, and Google Drive integration.

## Overview

Big Cat Newspaper Workflow extends [Calibre](https://calibre-ebook.com/) with automated newspaper processing and delivery capabilities.

The application is designed to simplify the process of preparing and distributing digital newspaper editions for personal reading.

## Features

- Automated processing of newspaper editions
- PDF generation and delivery
- Google Drive integration for file storage and sharing
- Email notifications containing links to generated PDFs
- Automatic cleanup of older Google Drive files
- Configurable file retention, with a default period of 60 days

## Google Drive Integration

The application uses Google OAuth 2.0 to authorize access to Google Drive.

Once authorized, the plugin can:

1. Upload generated newspaper PDFs to Google Drive.
2. Generate links for accessing uploaded files.
3. Send email notifications containing those links.
4. Remove files older than the configured retention period.

Google Drive access is used exclusively to support the application's newspaper delivery workflow.

## Installation

Big Cat Newspaper Workflow is a custom plugin developed for the Calibre ebook management application.

The plugin requires:

- Calibre
- A Google account for Google Drive integration
- Google OAuth 2.0 credentials
- Internet access for Google Drive uploads and email delivery

## Privacy and Security

Big Cat Newspaper Workflow is intended primarily for personal use.

Google OAuth credentials and authorization tokens are used to authenticate requests to Google Drive.

The application does not sell user information or use Google account data for advertising.

See [PRIVACY.md](PRIVACY.md) for additional information
