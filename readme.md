# Used Car Website

## Features

Display latest used cars for sale posts

1. build a web scraper for [auto tempest](https://www.autotempest.com/)

Search for used cars using #TODO

Create used car posting, exclusive to site

Create account:

- save postings you are interested in
- create postings(exclusive to site)

## Using

SvelteKit + TypeScript

PrismaORM

[SvelteKit Auth](https://authjs.dev/reference/sveltekit)

TailwindCSS

## Models

```typescript
interface User {
  userName: string; // unique
  hashedPassword: string; // need
  savedCars: Car[];
  postedCars: Car[];
}

interface Car {}
```
