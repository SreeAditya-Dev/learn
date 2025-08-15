# Contributing Guidelines

This repository has automated verification checks to ensure all contributions meet the required standards. When you create a new branch or submit a pull request, the following requirements will be automatically verified:

## Branch Verification Requirements

### 1. Commit Message Requirements

All commits in your branch must have proper commit messages that:

- **Are not empty** - Every commit must have a meaningful message
- **Are at least 10 characters long** - Messages should be descriptive enough
- **Are descriptive** - Avoid non-meaningful messages like ".", "1", or just spaces
- **Clearly describe what the commit does** - Help others understand your changes

#### Good commit message examples:
```
Add user authentication feature
Fix navigation bug in header menu
Update README with installation instructions
Refactor database connection logic
```

#### Bad commit message examples:
```
.
fix
1
update
   (empty or just spaces)
```

### 2. README File Requirements

Your branch must contain a README file that:

- **Exists** - Must have a README file (README.md, readme.md, or README.txt)
- **Has adequate content** - Must be at least 10 characters long
- **Explains your project/contribution** - Should describe what your changes or project are about

## How the Verification Works

The verification process runs automatically when:
- You push commits to any branch (except main)
- You open, update, or reopen a pull request

If your branch doesn't meet these requirements, the verification check will fail and you'll need to fix the issues before your contribution can be accepted.

## What Happens When Verification Fails

If the verification fails, you'll see:
- Clear error messages explaining what needs to be fixed
- Helpful guidance on how to meet the requirements
- The specific commits or files that need attention

## How to Fix Common Issues

### Fix commit messages:
If you have commits with poor messages, you can:
1. Use `git commit --amend` to fix the last commit message
2. Use `git rebase -i` to edit multiple commit messages
3. Create new commits with proper messages

### Fix missing README:
1. Create a README.md file in your repository root
2. Add meaningful content explaining your project or changes
3. Commit the README file with a proper commit message

## Getting Help

If you're having trouble meeting these requirements or have questions about the verification process, please:
- Review the error messages carefully - they contain specific guidance
- Check the examples in this document
- Ask for help in the repository issues or discussions

Thank you for contributing and helping maintain code quality!