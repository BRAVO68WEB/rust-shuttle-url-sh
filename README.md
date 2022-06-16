# b68-ufm-mc

Trying out [shuttle](https://www.shuttle.rs/), a serverless rust microservice framework.

## Plus Points

- No need to care about database
- Serverless
- Fast deploy times

## More Info

- Uses [Rocket](https://rocket.rs/) as to create Web Server

## What's Build here

A Url Shortener microservice 

### Create

```bash
curl -X POST -d '<URL>' https://b68-ufm-mc.shuttleapp.rs/
```

This returns shortened URL in the response

## Project Structure

    - src
        - main.rs
    - migrations
        - main
            - create_table.sql
    - Cargo.toml