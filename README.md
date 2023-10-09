# Trail // Track - API

This is the backend API for the 'Trail // Track' application.

## API

### User Authentication

| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| POST   | `/sign-up`             | `users#signup`    |
| POST   | `/sign-in`             | `users#signin`    |
| DELETE | `/sign-out/`        | `users#signout`   |

### Activities

| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| GET   | `/activities`             | `activities#index`    |
| GET  | `/activities/<act_id>` | `activities#show`  |
| PATCH  | `/activities/<act_id>` | `activities#update`  |
| POST   | `/activities/add_new`             | `activities#add_new`    |
| DELETE | `/activities/<act_id>`        | `activities#delete`   |

### User Comments

| Verb   | URI Pattern            | Controller#Action |
|--------|------------------------|-------------------|
| GET   | `/adventurecomment`             | `adventurecomment#index`    |
| POST   | `/adventurecomment/addnew`     | `adventurecomment#create`    |
| DELETE | `adventurecomment/comment_id`   |`adventurecomment#delete` |

## Main Application

Find information about the main application [here](https://github.com/rextsears/trail-track).