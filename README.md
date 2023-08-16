# quickly-docker-rails

### You can check Rails7 very quickly.

- We don't have to occurred any more errors to check for Rails behavior...
- We don't have to modify some codes after git clone...
- We don't have to read long README.md
- We don't have to start up mysterious container.

... Only the welcome page is needed.

# Step

```bash
git clone git@github.com:fooramu/quickly-docker-rails.git
cd quickly-docker-rails
docker-compose build
docker-compose up -d
docker-compose exec web rails db:create
```

# Contribute

If you have a more shortly construct ideas, please `fork`.
Thank you for all Rails engineer's.

<img src="https://github.com/fooramu/quickly-docker-rails/assets/434513/3309761d-c616-462c-b92d-4681bbb0ac18" width="30%">


