# ML Modeling Code Review

- [ ]  **Coding Principles**
    - [ ]  private methods are only used inside classes
    - [ ]  all methods are used
    - [ ]  all classes are used
    - [ ]  existing MLOPS framework is used/updated
    - [ ]  modularization is following the single-responsibility principle
    - [ ]  common functions are pulled from the correct place; it’s ok to reuse classes and create objects
    - [ ]  names are easy to read
    - [ ]  functions are not too short, not too long
    - [ ]  verify the solution architecture matches the code structure
- [ ]  **Config Files**
    - [ ]  config file is containing credentials
    - [ ]  a separate config is handling intermediate and final file storage paths
    - [ ]  a separate config file is containing hardcoded business parameters and hyperparameters
- [ ]  **Coding Standards, Commenting and Docstrings**
    - [ ]  Verify adherence to language-specific best practices (e.g., PEP 8 for Python).
    - [ ]  Docstrings for all functions and classes, detailing inputs, outputs, and purpose.
    - [ ]  Inline comments for complex logic.
- [ ]  **Documentation**
    - [ ]  README contains diagram of pipeline required for model training
    - [ ]  README contains instructions on running the code, machine/cluster specs and estimated time of completion
    - [ ]  README contains list of experiments that led to final model selection

# MLflow Model sign-off

- [ ]  Final experiment code linked to MLflow sign-off run
- [ ]  Metrics logged
- [ ]  Hyperparams logged
- [ ]  Dataset Schemas (features and target) are visible
- [ ]  Start, end dates of training, validation and test set are logged
- [ ]  MLflow experiment path in config
