# Testing localhost API of the simple store template with Postman/Newman and publishing results to the Github Actions

## [Report](https://teosoph.github.io/Postman-newman-ghActions/)

## Step to run

1. Clone repo `git clone `;
2. Run `npm i` (install node.js dependencies);
3. Run `npm run tern-on-api`(to run testing server locally );
4. Upload store.collection.json in Postman app;
5. Run collection.

### Overview

Routes `/products`, `/orders` and `/users`. Below is a table of supported operations with `products` as example resource. The same operations are also supports for `orders/` and `users/`.

| VERB   | Route         | Input      | Output             |
| ------ | ------------- | ---------- | ------------------ |
| GET    | /products     | _None_     | **Array**          |
| GET    | /products/:id | **e.g 3**  | **Object**         |
| POST   | /products     | **object** | **Created object** |
| PUT    | /products     | **object** | **Updated object** |
| DELETE | /products/:id | **e.g 3**  | **Deleted object** |
