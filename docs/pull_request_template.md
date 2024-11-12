## PR Checklist

### Notebook requirements

- [ ] **Secrets**: Ensure no secrets are exposed in your commit. Best practice is to use a `.env` file instead of hardcording secrets.
    - [ ] Check the `.pre-commit-config.yaml` file to ensure no secrets were detected upon comitting
- [ ] **Notebook cell execution counts cleared**: Ensure all notebook cell execution counts are cleared. This can be done by installing `python3 -m pip install nb-clean` and running `nb-clean clean --preserve-cell-outputs file-name.ipynb`.
- [ ] **Test locally**:
    - [ ] Ensure the code works in a fresh Python virtual environment (venv).

### GitHub

- [ ] **Commits signed**: All commits must be GPG or SSH signed.
- [ ] **DCO Compliance**: Developer Certificate of Origin (DCO) applies to the code, documentation, and any example data provided. Ensure commits are signed off.
