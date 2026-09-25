# Rails Practice

Practice projects for learning Ruby on Rails (Ruby 3.3, Rails 7.2).

## Apps

| Folder | Description |
| --- | --- |
| [`store/`](store/) | Store app following the Rails Getting Started guide |
| [`my_first_rails_app/`](my_first_rails_app/) | My first Rails app |

## Running an app

```sh
cd store            # or another app folder
bin/setup
bin/rails server
```

Then open http://localhost:3000.

## Adding a new practice app

Create it from this folder with `--skip-git`, so it doesn't get its own nested git repo:

```sh
rails new my_new_app --skip-git
```
