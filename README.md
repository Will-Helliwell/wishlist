# Node React Template Repository

A single repository with a Node.js backend and a React Frontend.

Can be used as a base and connected to any database as required.

## Stack

| Technology          | Use                           |
| ------------------- | ----------------------------- |
| Node                | Back-end JavaScript Framework |
| Express             | Web application framework     |
| React               | Front-end framework           |
| ESLint and Prettier | JavaScript Linting            |

## Setup

- Ensure Node.js is installed locally and clone this repository.
- Install backend dependencies - `npm install`
- Start backend locally - `npm run start`
- Install frontend dependencies - `cd client && npm install`
- Start frontend locally - `npm run start` (whilst still in client directory)

## Entity-relationship Diagram

![entity-relationship diagram](https://github.com/Will-Helliwell/wishlist/blob/main/wishlist_ER_diagram.jpg)

## User Stories

```
As a user
So that I can securely access my information
I want to log in

As a user
So that I can protect my information
I want to log out

As a user
So that I can remember the presents I want
I want to be able to add a presents to my area

As a user
So that I can keep tell which presents were for which year
I want to be able to assign presents to a wishlist

As a user
So that I can keep tell which presents were for which year
I want to be able to assign presents to a wishlist

As a user
So that I can keep track of my wishlists
I want to be able to view all of my wishlists

As a user
So that I can easily tell my friends what presents to get me
I want to be able to share a wishlist with multiple email addresses

As a user
So that I can easily invite people I know to a wishlist
I want to be able to add users I am already associated with

As a gifter
So that I can see a list that has been shared with me
I want to be able to see all lists that have been shared with me

As a gifter
So that I can sign up
I want to be quickly create an account

As a gifter
So that nobody buys the same present as me
I want to be able to mark a present as bought
```
