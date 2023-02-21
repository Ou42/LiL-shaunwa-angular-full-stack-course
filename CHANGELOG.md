## 2023-02-20

### started tutorial

- created angular project via:  
  `ng new buy-and-sell`
- tested with:  
  `ng serve -o`

### Create your first Angular component

- `ng generate component listings-page`
- inserted it using its selector into `app.component.html`
- tested with:  
  `ng serve -o`

### Routes and routing in Angular

- created a '/listings' route path
- `ng generate component ...`
  - `listing-detail-page`
  - `contact-page`
  - `my-listings-page`
  - `new-listing-page`
  - `edit-listing-page`
- created a 'listings/:id' route path
- created a 'contact/:id' route path
- created a 'edit-listing/:id' route path
- created a 'my-listings' route path
- created a 'new-listing' route path
- created a redirect for '' to '/listings'
- `pathMatch: 'full'` req for exact path matches

  