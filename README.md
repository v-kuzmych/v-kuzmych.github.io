# My CV
Available at [vasylyna.kuzmych.dev](https://vasylyna.kuzmych.dev) or [v-kuzmych.github.io](https://v-kuzmych.github.io).

### To preview/edit locally with docker

```sh
docker-compose up
```

*docker-compose.yml* file is used to create a container that is reachable under http://localhost:4000.
Changes *_data/data.yml* will be visible after a while.

### Local machine

* Get the repo into your machine 
```bash
git clone https://github.com/sharu725/online-cv.git
```
* Install required ruby gems
```bash
bundle install
```
* Serve the site locally
```bash
bundle exec jekyll serve
```
* Navigate to `http://localhost:4000`
