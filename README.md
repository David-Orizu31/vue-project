# Vue Jobs

A job listing application built with Vue 3 and Vite, following Brad Traversy's Vue.js Crash Course (2024).

## Features

- View all job listings
- View single job details
- Add a new job listing
- Edit an existing job listing
- Delete a job listing
- JSON Server as a mock backend REST API
- Toast notifications for user feedback
- Responsive design with Tailwind CSS

## Tech Stack

- [Vue 3](https://vuejs.org/) - Progressive JavaScript Framework
- [Vite](https://vitejs.dev/) - Next Generation Frontend Tooling
- [Vue Router](https://router.vuejs.org/) - Official Router for Vue.js
- [Tailwind CSS](https://tailwindcss.com/) - Utility-First CSS Framework
- [JSON Server](https://github.com/typicode/json-server) - Full Fake REST API
- [Axios](https://axios-http.com/) - Promise Based HTTP Client
- [Vue Toastification](https://github.com/Maronato/vue-toastification) - Toast Notifications

## Project Setup

```sh
npm install
```

### Run JSON Server (Mock Backend)

```sh
npm run server
```

> Runs on http://localhost:5000/jobs

### Compile and Hot-Reload for Development

```sh
npm run dev
```

> Runs on http://localhost:3000

### Compile and Minify for Production

```sh
npm run build
```

## Project Structure

````
vue-jobs/
├── public/
├── src/
│   ├── assets/
│   ├── components/
|   |   ├── BackButton.vue
|   |   ├── Card.vue
│   │   ├── Hero.vue
│   │   ├── HomeCards.vue
│   │   ├── JobListing.vue
│   │   ├── JobListings.vue
│   │   └── Navbar.vue
│   ├── router/
│   │   └── index.js
│   ├── views/
│   │   ├── AddJobView.vue
│   │   ├── EditJobView.vue
│   │   ├── HomeView.vue
│   │   ├── JobsView.vue
│   │   ├── JobView.vue
│   │   └── NotFoundView.vue
│   ├── App.vue
│   └── main.js
├── jobs.json
├── package.json
└── vite.config.js
````

## License

MIT

## Acknowledgements

- [Brad Traversy](https://www.youtube.com/watch?v=VeNfHj6MhgA) - Vue.js Crash Course (2024)
- [Traversy Media](https://www.youtube.com/@TraversyMedia) on YouTube