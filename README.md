# DeletedBot Docker

For all the folks that can't live without **containerization**, here's a **Docker** container for DeletedBot's backend code.
With a single `docker-compose up` you can now deploy both the backend code as well as the redis database in one go.

## How to deploy

1. Clone the code of this repository
2. Rename the file `.example_env` to `.env` and edit the values as you please
3. Clone the [backend](https://github.com/deleted-bot/backend) repository in a folder called `src`
4. Run `docker-compose up` and you're good to go.