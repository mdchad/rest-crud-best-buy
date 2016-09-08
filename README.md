# Best Buy CRUD REST Inventory Manager
Build a website that manages the product inventory for a Best Buy store.
The store has a list of products which it stores in a JSON file.

We're making a web tool that allows users to view all the products,
view the details of one product, and edit the details of one product.
We'll achieve all of this by implementing a RESTful interface.

## Project Setup
Install all of the project dependencies by running `npm install`. Use
`nodemon index.js` to start the server.

## Add Product Quantity
Now that you've got full RESTful CRUD app you will mimic it's
operations and add a new `quantity` property to the products.

You'll need to do several things to achieve this:

- Go to the `products.json` file and add `quantity: 0` (or some number) to all
  existing products.
- Add new input forms to the item detail view that displays the current
  quantity of items.
- Add a new input form to the edit template that renders the current quantity of
  the item as the value attribute for the input element.
- Add a new input form to the product create page that allows users to input
  a quantity when creating a new product.

That should be it. Good luck!

## Licensing
All content is licensed under a CC­BY­NC­SA 4.0 license.
All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.

