# Insight 

Welcome to the Insight home in the Ortus Telematics organisation on GitHub. This is a space where we create awesome projects and collaborate with each other to power up our Insight platform.

It's crucial to protect your source code, especially when it's commercially sensitive. Please ensure you follow Ortus's Cyber Office security recommendations to keep your code safe. These are summarised below:

Do ✔️

- Limit access to your repositories to approved Ortus Telematics staff and 3rd parties. Remember to remove access when no longer required.
- Ensure privileged roles such as admin and maintainer are restricted.
- Enable MFA for your GitHub account.
- Protect your main branch with branch protection rules such as:
  - Requiring a pull request before merging.
  - Requiring pull request approvals before merging.
  - Requiring status checks to pass before merging.
- Consider using a codeowners file to define who is responsible for certain code in a repository. You can then request review from a codeowner when pull requests are created that modifies code they own.
- Prefer fine-grained personal access tokens over classic personal access tokens. Fine-grained access tokens give access to a subset of repositories rather than every repository your account has access to.
- Use code scanning tools where possible. If you're using public repositories, you can use GitHub code scanning to scan for vulnerabilities and secrets in your code.
- Keep dependencies up to date. You can use GitHub's dependabot to help with this.
- If using GitHub Actions, review Ortus's best practises for keeping your workflows secure.

Don't ❌

- Store secret credentials in your source code. If you do accidentally commit a secret, make sure you regenerate it. Even if you delete the secret, it will still exist in the commit history and any forks of your repository.
- Store personal data or special category (sensitive) data in your source code. GitHub is not designed for storing sensitive data. Storing this kind of data in GitHub could be a breach of GDPR regulations. Instead, personal/sensitive data should be stored in encryted databases, secure cloud storage (e.g. Azure Blob Storage, AWS S3) or other secure data stores.
- Use public repositories for sensitive projects.
