LANGUAGE PICKED = PYTHON

1. *Some common steps in a CI setup include linting, testing, and building. What are the specific tools for taking care of these steps in the ecosystem of the language you picked? You can search for the answers by Google.*

- Linter's for python include PyLint and Ruff. 
- Tools for testing python packages include PyTest
- For building packaging tools, setuptools is usually used. 

2. *What alternatives are there to set up the CI besides Jenkins and GitHub Actions? Again, you can ask Google!*

- Alternatives include GitLab and Azure DevOps Server

3. *Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?*

- Both options have their advantages. For example, if the set up is hosted on a cloud-based environment, the costs to keep it running are not that expensive, especially if you don't need many CPU's/ cores. That being said, it is arguably risky as you are relying on the fact that the cloud provider will stay in business in the medium-long term future, which may not be the case, in which case, self-hosted may pose as a better alternative, especially if its really sensitive information/ information you cant risk losing. Also, cloud-based providers may change their prices mid way through, in which case the advantages of low-cost may not be found. Although this may be the case, because of the large amount of alternative cloud providers, switching to cost-cut is a very effective response to this. 