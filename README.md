# parameterized-manual-workflow
Create a manually triggered GitHub Actions workflow that accepts user-defined inputs, shares data between jobs using job outputs, and conditionally executes downstream jobs based on those outputs.
This simulates a real-world CI/CD scenario where a workflow must:

- Be triggered manually (not automatically)

- Accept runtime parameters

- Perform a validation step

- Decide whether to proceed based on validation results

learn how job-to-job communication works in GitHub Actions and how execution flow can be controlled dynamically.
