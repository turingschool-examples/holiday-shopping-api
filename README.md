# Holiday Shopping API

This repo was created to be used with the winter break advent calendar.

## Set Up

* Clone this down
* `cd` into the repository
* `npm install`
* `npm start`

## Endpoints

| Description | URL | Method | Required Headers | Required Properties for Request | Sample Successful Response |
|----------|-----|--------|-----------------|---------------------|-----------------|
| Get all items |`http://localhost:3001/items`| GET  | none |  none | An array containing all items |
| Add item |`http://localhost:3001/items` | POST  | `'Content-Type': 'application/json'` | `{ id: <number>, recipient: <string>, name: <string>, priceInDollars: <number> }` | "Item #<id number here> has been added!" |

