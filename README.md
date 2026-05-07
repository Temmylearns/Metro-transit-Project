# Metro Transit Next Bus

A small Go command-line project that fetches Metro Transit route, direction, stop, and departure data from the Metro Transit NexTrip API.

## Purpose

This project was created to get familiar with Go (Golang) by building a real-world application that consumes HTTP APIs, parses JSON responses, and interacts with the user through the terminal.

## What it does

- fetches available bus routes from the Metro Transit NexTrip API
- allows the user to select a route by ID or label
- accepts a direction input (`north` or `south`)
- finds stops for the selected route and direction
- fetches the next departure time for a selected stop
- displays an estimated arrival time in minutes

## How to run

1. Install Go if you do not already have it: https://go.dev/dl/
2. Open a terminal in the project folder.
3. Run the program:

```bash
go run nextBus.go
```

4. Follow the prompts:

- enter a route ID or label
- enter a direction (`north` or `south`)
- enter a bus stop description

## Notes

- The program uses the public Metro Transit NexTrip API: `http://svc.metrotransit.org/NexTrip`
- It is intentionally simple and focused on learning Go fundamentals like `http`, `json`, `bufio`, and basic control flow.

## License

This project is provided as a learning exercise and does not include a license file.
