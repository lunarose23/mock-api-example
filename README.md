# Mock API Example

This is an example Mock API for rapid front-end development. I walk through how to build this from scratch in [Building a JavaScript Development Environment](http://app.pluralsight.com/author/cory-house) on Pluralsight.
https://medium.freecodecamp.org/rapid-development-via-mock-apis-e559087be066

## Quick Start

1. Change port in package.json to what port you want it on
   Update schema 
    - build schema here to test before updating mockDataSchema.js under build scripts https://json-schema-faker.js.org/
    - Faker.js, chance.js, and randexp.js are libraries that will help with schema creation
2. `npm install`
3. `npm start`
4. Load http://localhost:3001/users

## Next Steps

Generate PUT, POST, and DELETE requests against the mock API and note that changes are saved to db.json, so they're reflected on refresh like a real database exists! To see this in action, check out [Building a JavaScript Development Environment](http://app.pluralsight.com/author/cory-house) on Pluralsight.

## Hosting

For hosting info, check out [json-server-heroku](https://github.com/jesperorb/json-server-heroku).
