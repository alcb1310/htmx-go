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
