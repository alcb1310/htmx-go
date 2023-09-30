# Budget Control Application Full Stack Application

## Tech Stack

For this application we will be using the following stack:

- Go
- HTMX

## Build Process

Two commands have to be executed in order to properly build this application:

```bash
go build -o out main.go
npx tailwindcss -i ./src/input.css -o ./dist/output.css
```

Remember to run both commands or you will ***NOT*** have any styles since we are using **Tailwind** to style our pages

## Development Build Process

To run in development we will need to run the following commands **after** each change we make

```bash
go run main.go
```

The following command will generate the required css when any change is made to the corresponding HTML


```bash
npx tailwindcss -i ./templates/input.css -o ./dist/output.css --watch
```

