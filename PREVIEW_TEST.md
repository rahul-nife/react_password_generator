# Preview Environment Test

This is a test pull request to verify Nife PR Preview Deployments (NIFE-4107), mirroring Render's preview environments.
- Automatically spins up an isolated preview deployment on PR open/sync.
- Injects preview-specific environment variables.
- Tears down automatically when the PR is closed or merged.
