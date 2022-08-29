<h1>Pipeline process documentation</h1>

<h3>We are using CircleCi in this project to make the pipeline</h3>

1. The process starts by installing important recipes in the orbs of CirclCi to initiate the environment the code will run in. These recipes are node, EB cli, and AWS cli.

2. Then an image of there is an image in the docker that is built in the jobs section of the CircleCi pipeline to run most actions.

3. In the steps section of the jobs, node is installed at a specific version (14.15).

4. The building steps are ran to install and prepare the app for deployment. These steps are installing the front-end modules, the api modules, linting the front-end, building the front-end and the back-end (api).

5. Then the deploying step is ran. In order to deploy the app, eb cli, aws cli, node, and checkout are installed.