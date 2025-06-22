# Welcome to bobak-labs!
Hi there! Feel free to join in and propose new projects - we are open to new challenges and ready to collaborate, discuss and share anything related to tech!
## Contribute
If you want to propose any project/change, please submit a PR or Issue with a project description + details for this repository with a description `project proposal <project_name>`. Proposals for new projects should be submitted within this repo on branch `project-proposals`.

## Join the organization
To join, create a pull request with your github name in the `users.toml` file (from forked repo) on [this branch](https://github.com/bobak-labs/.github/tree/membership-requests) or create an issue in [this repository](https://github.com/bobak-labs/.github) with the name `membership request <your_github_login>`.

## 🧠 Guidelines for Collaboration

To ensure smooth collaboration and maintain high-quality projects at **Bobak Labs**, please follow these best practices:

---

### 1. **Write Clear Commit Messages**

- Use descriptive commit messages that explain the _why_ behind a change.
- Follow a consistent format like:

    ```
    feat: add file sharing with expiration date  
    fix: handle 403 error from GCS properly  
    refactor: extract auth logic into middleware
    ```

---

### 2. **Follow Code Style Guidelines**

- Respect established formatting and linting rules (e.g., `gofmt`, ESLint).
- Avoid large unrelated refactors in PRs focused on a specific feature.

---

### 3. **Keep Pull Requests Focused and Small**

- Submit one feature or fix per pull request.
- Avoid bundling unrelated changes into a single PR.

---

### 4. **Use Branch Naming Conventions**

Use consistent, descriptive branch names:

- `feature/share-links`
- `bugfix/auth-token-refresh`
- `chore/update-deps`

---

### 5. **Review Thoroughly and Constructively**

- Be respectful and helpful during code reviews.
- Ask clarifying questions instead of making demands.
- Offer reasoning behind suggested changes.

---

### 6. **Write or Update Documentation**

- Update `README`, code comments, or API docs when introducing new features or changes.
- Document any changes that affect usage, configuration, or APIs.

---

### 7. **Test Before You Push**

- Ensure all tests pass before pushing changes.
- Manually test your feature if applicable (especially for UI or file interactions).

---

### 8. **Respect Ownership and Approval Flows**

- Do not merge your own PRs unless you have explicit permission.
- Request reviews from appropriate maintainers or code owners.

---

### 9. **Avoid Breaking Changes**

- Clearly document and communicate any breaking changes.
- Provide backward-compatible alternatives when possible.

---

### 10. **Stay in Sync with Main**

- Regularly rebase or merge from `main` to keep your branch up to date.
- Resolve conflicts early to avoid blocking progress.

---

### ✅ Required Practices

- Always create a PR for every new feature or change.
- Do not push directly to the `main` or `master` branches.
- If you find bugs, security issues, or room for improvement, create an issue or PR in the appropriate repo.
