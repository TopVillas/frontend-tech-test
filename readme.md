# Top Villas Tech Test

Welcome to the Top Villas javascript test, we expect this test to take a couple of hours, we aren't looking for perfection, we're more interested in the methods used to achieve the tasks set out, we will however merit attention to detail.

Please commit regularly so we can see how you structure working through a project.

### 1. Node.js Backend

_Challenge located in the `server` directory._

For the backend part of this test you are free to use any flavour of Node.js, the API should return the data supplied within the `server/data` directory. You will notice two files here:

- **Amenities** - These are specific features a property has users of the site are keen to filter their search by.
- **Listings** - This contains all of the property listing data.

For each of these data sets you'll need to consider how to best return them (directly from the JSON file is completely fine, no need to use a database).

The server example has node / express installed ready and running on port `8000`, feel free to modify this as required.

**Considerations**

- Separation of concerns for each module (`listings`, `amenities`).
- Handling larger data sets (such as the `listings` data).

### 2. Frontend Client App

_Challenge located in the `client` directory_

For the front end website application we'd simply like you to follow the design and consume the `server` API.

Feel free to use plain CSS or Tailwind (this is installed in the next.js project) either is completely fine. Although the design looks beautiful, we'd rather you spend the bulk of your time implementing the backend and using common react / next.js patterns to consume, display and manage the front end client experience.

[The design can be found here](https://www.figma.com/file/1sHgWMWujfOBrsR3cBhCim/Tech-Test?node-id=1:2)

All of the assets are contained with-in the `client/public/img` directory, the listing images are located on our production servers.

**Considerations**

- Component based architecture
- Loading of remote image resources
- Pagination through the API
- Filtering search results (this can either be done in the backend or client).

**Out of scope**

- The listings do not need to go to a details page
