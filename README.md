# Vanya

Backend developer. Most of my code lives in private repos at the places I've
worked, so what's here is side projects and things I could put out publicly.

Five years of backend. Rust on a depth camera platform. Two years of Java
against databases large enough that the obvious query stops being an option.
Node.js holding up a classroom monitoring product with a lot of devices
reporting at once.

These days it's mostly Python: parsers for proprietary binary and ASCII formats,
validation and normalisation into PostGIS, and geospatial pipelines on GDAL,
GeoPandas and Shapely. Turns out the interesting problems are in file format
edge cases and in whoever decided that field could be either a float or the
string "N/A".

**Stack:** Rust, Python, Java, C#, TypeScript, Node.js, Angular, PostgreSQL,
PostGIS, MongoDB, Docker, Jenkins

### Rust

Most of my Rust comes from a depth camera platform. Backend services and the
business logic behind them, the database layer underneath, GraphQL APIs on top,
and a decent amount of low level code talking to the device itself.

I also worked on the SDK that external developers build against. That's a
different job from writing a service. Nobody reads your internals, they read
your function signatures, and once someone ships against those you don't get to
change your mind. Naming things stops being a joke and starts being the work.

None of it is public, which is the usual situation with anything written on
company time.

### Projects

**[FinanceMe](https://github.com/BenTheShork/FinanceMe)** — personal finance
tracker in Django. Calendar view, categories, spending breakdowns. Built it
because I wanted one and the existing apps all wanted a subscription.

**[ExpenseSense](https://github.com/BenTheShork/ExpenseSense-)** — scikit-learn
on top of the same data, predicting spend per category. Small scale, but the
pipeline is honest.

**[Golem's Dominion](https://github.com/BenTheShork/Golem-s-Dominion)** —
top-down adventure game in plain JavaScript. No engine, no framework, mostly to
find out how far you get without either.

### Elsewhere

Bowie and Bauhaus, currently going through Ulysses again, and two budgies who
supervise the whole operation.

Messages about backend work or Rust are welcome.
