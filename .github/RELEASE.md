# Release Flow

This documents the release flow for the maintainers. If you're not a maintainer,
you don't need to read this.

To cut a release, follow these steps:

1. Fix any lint errors (slow-types etc.):
   ```sh
   deno publish --dry-run
   ```

2. Create a release branch, bump the version and land the PR

3. Create a release from GitHub

4. Wait for the workspace publish action to publish the new versions to JSR.
