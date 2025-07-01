I have chosen Python. Here is the discussion about the CI/CD setup:

1. CI Tools
For linting in Python, common tools are Flake8 and Pylint. These tools help to check the code for style issues and potential bugs. For testing, pytest is a widely used framework that supports simple unit tests as well as complex scenarios. When it comes to building, Python projects are often packaged into "wheel" files using tools like setuptools and wheel, which makes them easy to distribute and install.

2. Other CI platform choices
Besides Jenkins and GitHub Actions, there are other good options. For example, GitLab CI/CD works very well with GitLab repositories, making it convenient for teams already using GitLab. Another alternative is CircleCI, which offers fast and scalable cloud-based pipelines.

3. Cloud-Based or self-Hosted
For a small team of six people, a cloud-based service is usually better. It removes the need to manage and maintain CI servers, allowing the team to focus on coding and delivering features faster. However, to make this choice, the team should consider factors such as budget, security policies, and compliance needs. If sensitive data is involved, the team must ensure that the cloud provider meets all required security standards.