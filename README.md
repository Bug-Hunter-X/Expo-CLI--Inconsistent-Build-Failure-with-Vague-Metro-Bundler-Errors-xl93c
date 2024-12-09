# Expo CLI: Inconsistent Build Failure with Vague Metro Bundler Errors

This repository demonstrates an uncommon bug encountered while using the Expo CLI. The build process intermittently fails without providing clear error messages from the Metro bundler, resulting in an indefinite hang.

## Problem

The Expo build process hangs indefinitely without providing any useful error messages within the logs or via the Expo CLI. This issue is not consistent; sometimes, the build completes successfully, and other times, it fails without any discernible pattern or code changes.

## Solution

The provided solution explores several potential remedies that may resolve this intermittent build failure.  These include checking for issues with dependencies, clearing the cache, and ensuring proper project setup. Detailed steps are included in the `bugSolution.js` file.

## Steps to Reproduce

1. Clone the repository.
2. Run `npm install`.
3. Attempt to build the project using `expo build:android` or `expo build:ios`. Observe the inconsistent build behavior.
4. Implement the solution steps in `bugSolution.js` to address the issue.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you encounter similar problems or have alternative solutions.