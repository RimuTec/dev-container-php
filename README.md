# dev-container-php
An opinionated dev container for PHP development with VS Code

## Run PHP as Script

Go to ./src then run the following command:

```bash
./hello.php
```

## Run PHP from Web Server

Got to ./src then rune the following command to start the the development server:

```bash
php -S localhost:3000
```

Then point the browser to `localhost:3000`.

# Prerequisites

You need the following prerequisites on your computer:

1. VS Code
2. Docker Desktop (MacOS, Windows) or docker engine (Linux)
3. VS Code extension for remote development
4. git client

With this setup VS Code will suggest re-opening in the dev container when you open the repo's local clone's directory in VS Code.

Other setups may work as well but were not considered for this sample repository.
