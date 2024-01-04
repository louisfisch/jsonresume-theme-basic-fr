# Basic theme in French for JSON Resume

Basic theme in French for JSON Resume is very ... basic. It can therefore be used both as a theme and boilerplate. The theme covers every single key of the [JSON Resume schema](https://github.com/jsonresume/resume-schema).

## Usage

### Theme

1. Make sure you have `resume-cli` installed

        npm install -g resume-cli

2. Install the theme

        npm install jsonresume-theme-basic-fr

3. Serve your resume using the theme Basic

        resume serve -t basic-fr

### Boilerplate

#### Using Docker

1. Download the repository and change the current working directory

        git clone https://github.com/louisfisch/jsonresume-theme-basic-fr.git && cd jsonresume-theme-basic-fr

2. Build the image then build, create and start the container in detached mode (container will run in the background)

        docker compose up --build --detach

3. Copy and paste your `resume.json` file in the current working directory

4. Serve your resume using Basic theme in French

        docker exec jsonresume-theme-basic-fr resume serve -t .

#### Using your own environment

1. Make sure you have `resume-cli` installed

        npm install -g resume-cli

2. Download the repository and change the current working directory

        git clone https://github.com/louisfisch/jsonresume-theme-basic-fr.git && cd jsonresume-theme-basic-fr

3. Copy and paste your `resume.json` file in the current working directory

4. Serve your resume using Basic theme in French

        resume serve -t .
