# DevSecOps December 2024 - Polytech

## Disclaimer
This is code is a copy of a tutorial from github.
It contains INTENTIONAL security findings but none of them are active.
This is for EDUCATION purpose.

## Exercice

### Exercice 1 : Hello World

1. Create a workflow file
2. EXIT : the workflow must PASS and echo the content of `hello_world.txt`

#### Results
- Workflow code
- URL of the BUILD (https://github.com/...../actions/runs/12098085715)


### Exercice 2 : Build and Test

1. Create a new workflow file
2. The workflow must build (`npm build`) the application in 1 step and execute tests (`npm test`) in another
3. EXIT : All workflows RUN needs to be passing

#### Results
- Workflow code
- URL of the BUILD (https://github.com/...../actions/runs/12098085715)


### Exercice 3 : Execute SCA
This exercice is NOT in the previous tutorial but based on the previous exercice. The goal is to run an SCA, find vulnerabilities and fix them.

1. Update the workflow from exercice 2
2. The workflow must execute an SCA to find vulnerabilities in dependencies
3. The code needs to be fixed to update (or remove) the vulnerable dependency
4. EXIT : All workflows RUN needs to be passing

#### Results
- Workflow code
- URL of the BUILD (https://github.com/...../actions/runs/12098085715)
- SCA finding (dependency name and version)


### Exercice 4 : Execute a SAST
This exercice is NOT in the previous tutorial but based on the previous exercice. The goal is to run an SAST, find a vulnerability and fix it.

1. Update or create a new workflow
2. The workflow must execute a SAST to find issues in code
3. The code needs to be fixed to remove the finding
4. EXIT : All workflows RUN needs to be passing

#### Results
- Workflow code
- URL of the BUILD (https://github.com/...../actions/runs/12098085715)
- SAST finding (file + line + CWE)