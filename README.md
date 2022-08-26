# validate-23535

## Validation Steps

1. Start Docker
2. `docker image build -t validate-23535:1 ./`
3. `docker run -it validate-23535:1` - should find and execute spec in project

### Extra Credit
4. Update Dockerfile to install 10.6.0 rather than fixed binary
5. `docker image build -t validate-23535:1 ./`
6. `docker run -it validate-23535:1` - should fail with

> Can't run because no spec files were found.
> We searched for specs matching this glob pattern:
> /cypress/**/*.cy.js
