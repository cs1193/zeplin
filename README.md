# Zeplin

We require **Docker & Docker Compose** to run the app.

## Running the app

Download and submodule init -

`git clone https://github.com/cs1193/zeplin.git`

`cd zeplin && git submodule update --recursive --remote`

Inside the WORKDIR, run below to build -

`docker-compose up --build -d`

**IMPORTANT** To seed data, on your browser, goto -

`http://localhost:38143/api/setup`

UI is accessible at -

`http://localhost:38141/#!/`

*UN: admin@zeplin.dev*
*PW: password*

Click Boards Dropdown > Choose `Example` seed board

> NOTE: There is limited functionality and limited tests covered.

--------------------------------------------

## Codebase

> API - https://github.com/cs1193/zeplin.api

> UI - https://github.com/cs1193/zeplin.ui

> DB - https://github.com/cs1193/zeplin.db

--------------------------------------------
