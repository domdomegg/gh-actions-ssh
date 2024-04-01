# gh-actions-ssh

Repo to test things inside GitHub Actions runners via SSH

## Usage

1. Click 'Run workflow' in [GitHub Actions's Run workflow](https://github.com/domdomegg/gh-actions-ssh/actions/workflows/run.yaml)
2. Open the running workflow, then the 'build' step
3. Find the log output that looks like: `ssh -i <path-to-private-SSH-key> abcdef@nyc1.tmate.io`
4. Login to the session using your GitHub SSH keys with that command, for example: `ssh -i ~/.ssh/id_ed25519_github abcdef@nyc1.tmate.io`
