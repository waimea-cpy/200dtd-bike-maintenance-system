# Bike Maintenance Tracker

by Steve Copley

![](docs/screenshots/yeti.jpg)


---

## Project Description

This project covers the development of a system that allows someone to track maintenance jobs for their bikes.

- Bikes can be added to the system
- Maintenance tasks can be defined for the bikes and added to the system
- Tasks can be one-offs or can be repeating ones
- Tasks that have not yet been completed are clearly listed
- Tasks can be marked as completed
- When a repeating task is marked as complete, it will be marked as incomplete again after a set amount of time


---

## Project Links

- [GitHub repo for the project](https://github.com/waimea-cpy/200dtd-bike-maintenance-system)
- [Project Documentation](https://waimea-cpy.github.io/200dtd-bike-maintenance-system/)
- [Live web app](https://...)


---

## Project Files

- Program source code can be found in the [app](app/) folder
- Project documentation is in the [docs](docs/) folder, including:
   - [Project requirements](docs/0-requirements.md)
   - Development sprints:
      - [Sprint 1](docs/1-sprint-1-prototype.md) - Development of a prototype
      - [Sprint 2](docs/2-sprint-2-mvp.md) - Development of a minimum viable product (MVP)
      - [Sprint 3](docs/3-sprint-3-refinement.md) - Final refinements
   - [Final review](docs/4-review.md)
   - [Setup guide](docs/setup.md) - Project and hosting setup

---

## Project Details

This is a digital media and database project for **NCEA Level 2**, assessed against standards [91892](docs/as91892.pdf) and [91893](docs/as91892.pdf).

The project is a web app that uses [Flask](https://flask.palletsprojects.com) for the server back-end, connecting to a SQLite database. The final deployment of the app is on [Render](https://render.com/), with the database hosted at [Turso](https://turso.tech/).

The app uses [Jinja2](https://jinja.palletsprojects.com/templates/) templating for structuring pages and data, and [PicoCSS](https://picocss.com/) as the starting point for styling the web front-end.

The project demonstrates a number of **advanced database techniques**:
- Linking data in related tables or nodes using queries or keys
- Writing custom queries to filter and/or sort data
- Using logical, mathematical and/or wildcard operators
- Customising presentation of the data
- Using custom forms to add user input to the database
- Setting validation rules for data entry

The project demonstrates a number of **advanced digital media (web) techniques**:
- Creating or customising scripts, code or presets
- Using a combination of steps to manipulate or enhance elements
- Using a third-party library
- Using composite effects



