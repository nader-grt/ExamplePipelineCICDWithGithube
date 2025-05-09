# 🚀 ExamplePipelineCICDWithGithube  (with GitHub Actions Build → Test → Deploy)

This project demonstrates a simple HTML web page deployed through a **multi-job GitHub Actions workflow**. The CI/CD pipeline automatically performs **build**, **test**, and **deploy** jobs on every push to the `main` branch.

## 🛠 GitHub Actions Workflow Overview

The workflow is defined in `.github/workflows/deploy.yml` and includes:

- **Build job**: Simulates building the project
- **Test job**: Runs after the build job to simulate tests
- **Deploy job**: Executes only after both build and test succeed

### 📄 Workflow YAML

```yaml
name: multi-job-demo-with-Nader

Build: Checks out the code and simulates a build step.

Test: Runs after the build job to simulate testing.

Deploy: Executes only after both build and test complete successfully, simulating deployment of index.html.




## 👤 Author

**Nader GRT**  
GitHub: [@nader-grt](https://github.com/nader-grt)

## 💻 How to Work with This Project Locally

1. **Clone the repository**:
 
 git  git clone https://github.com/nader-grt/ExamplePipelineCICDWithGithube.git
   cd ExamplePipelineCICDWithGithube
