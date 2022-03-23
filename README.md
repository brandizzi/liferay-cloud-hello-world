0. go to console.liferayclould.dev, create an accoutn with your email.
0. Go to mailhog.liferaycloud.dev, see the sent email, open the link from the invitation in a private window, and create your account.
1. run `lcp login`. (If already logged in as owner, `lcp logout`).
2. Create a project through the Liferay DXP console: go to console.liferaycloud.dev, log in, click in "New Project"
3. Create a new environment: to to the name of the projec tin the top left, there will be an option to create enviroments ehtere.
5. run `lcp deploy --project=<name of the project you have created> --environment=<environment-name>`
6. go to console, general, click on the running deployment, ask it to be deployed into the dev environment.
