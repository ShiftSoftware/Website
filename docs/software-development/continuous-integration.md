We organize our entire work process and company culture to adapt for Continuous Integration.  
We'll not discuss our work culture here since it's explained in [Tasks](/software-development/tasks). But we'll focus on how we apply CI (Continuous Integration):

* We divide work into small batches, commit, and merge them to main branch. This is a method known as <a href="https://cloud.google.com/architecture/devops/devops-tech-trunk-based-development" target="_blank">Trunk Based Development</a>.
* There are Build Pipelines in place that are triggered when code is merged to the main branch.
* The Build Pipeline executes all the [Automated Tests](/software-development/automated-testing) available in the source code. If the tests fail the developers are notified and the build pipeline is canceled.
* Developers are responsible for keeping the build process up and running. If a build fails, fixing the problem becomes the most prioritized task.
* Developers make sure that the main production branch is always in a **Releasable State** to enable [Continuous Delivery](/software-development/continuous-delivery).