# ap-greenfield
Submission for 'takehome' task of job interview. An example repository for the development of an 'A-B testing' feature 

## Repo layout

This is a monorepo, containing work on the frontend, backend services, and model development/deployment. They all
live in their own directories, together with one for shared code and general utilities.

The frontend at the moment is only a customer portal, but there is scope for adding further frontends if necessary.

### Frontend

To run:

```
cd frontend/customer_web
npm run dev
```

To typecheck:

```
npm run typecheck
```

To lint:
blah blah blah

### Backend

In short, to get something running:

```
docker compose --profile mock-backend up
```

See readme in backend for more details

### Models

# TODO add details of building models here

### Utils

Just a place to put useful utilites, please ensure that '--help' on command line utilites gives a good description of how they should be used

### Tests

Where end to end tests are located

## Process

Work on a separate branch. When ready raise a PR, feel free to put who you feel is best placed to review on the PR. The pipeline will run
so please correct any test failures/linting errors. Please title your branch with the issue that is being addressed by the PR, if relevant.

Implementation discussions should take place on the wiki/within issues.
