lingreference.org
=================


# Overview

## Purpose

- Translate linguistic terminology in Romance languages
- Provide community forum for consulting/suggesting/discussing translation
- Made by end-user for end-user (i.e. linguists)

## Current practices

- Reverse wikipedia + google search
- Find articles/books
- Ask a prof/advisor/lab buddy
- Wing it

## Problems with current practices

- Wikipedia only has entries in russian
- No pertinant articles/books in TL
- (linguistic) God complex
    - reliance on specific translation because it's what somebody else said first (Chomsky, Bosque, etc.)
    - doesn't take into account that it might not be a good translation
- Prof/advisor/lab buddy doesn't know/care

## What we need

- Forum where end-users (linguists) discuss, propose and rate translations of linguistic terminology

Possible consequences:  

- Eliminates God complex?
- Creates a database that formed by linguists that can be accessed by linguists (students, profs)

# The interface

## KISS

- Minimalist design
- Intuitive
- Accesible from mobile devices

##

<div align="center">
<img width="950" src='../images/home.png'>
</div>

##

<div align="center">
<img width="950" src='../images/entry.png'>
</div>

##

<div align="center">
<img width="950" src='../images/null.png'>
</div>

# Database

## How it works

- User submissions
- Staging
- Revision
- Inclusion

##

<div align="center">
<img width="950" src='../images/database_wf/database_wf.pdf'>
</div>

## Searching

- Query sent to database through PHP
- Database searched for 'x' term
- Result sent back to webpage through PHP

##

<div align="center">
<img width="950" src='../images/database_search/database_search.pdf'>
</div>

## Submission process

- Required info collected for each submission
    - SL entry
    - TL entry
    - meaning
    - example usage
    - references
    - tags

# Roadmap

## Functionality

- Rating system
    - 'thumbs up'/'thumbs down'
    - Display % 'thumbs up' with each entry
    - Rating occurs in entry, but accessible from forum
- Include multiple possibilities/translations for each entry (if suggested by users)
    - Ex.
        - English: 'voice-onset time'
        - Spanish: 'tiempo de inicio de sonoridad'/'tiempo de inicio de fonación'
    - Entries listed vertically, in order of highest rating
- Entry count in 'about' section
- Google form to submit entries (same excel as staging)
    - Submissions come from:
        - forum
        - search results (if it's not there, they can add it)
- Definitions
    - Include English definition with each entry

# Goals

##

<div align="center">
![internet gif](../images/internet.gif)
</div>

## Short term

- Functional dictionary with limited entries
- Build forum
- Promote to linguists
    - facebook
    - twitter

## Long term

- Become principle reference for linguistic terminology in Romance
- Grow user base
- Serve as model for language revitalization projects
    - open source code (github)
    - article (Comanche)

## References

- lots
- and lots


NOTES
- the community establishes authority (Kiraly 2003)