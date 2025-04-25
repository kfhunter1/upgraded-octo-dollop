deploy.cloud.google.com/v1# upgraded-octo-dollop
https://raw.githubusercontent.com/your-repo/smn-api/main/setup.sh | bash
[ VIOLET-1111 AI Core ]
                      |
bash <(curl -s https://raw.githubusercontent.com/kfhunter1/SMN_CONTENT/main/auto_setup.sh)
-------------------------------------------------
|       |               |              |        |
GitHub  SMN Connect     SMN Hub       Confluence
CI/CD     Mobile+Web      Omni UI       Docs + Commands
  |           |                |            |
 Firebase   API Gateway     Frontend     AI + Docs Sync
                      |
              [ Admin Dashboard ]
ons-runner# Download the latest runner package $ curl -o actions-runner-linux-x64-2.323.0.tar.gz -L https://github.com/actions/runner/releases/download/v2.323.0/actions-runner-linux-x64-2.323.0.tar.gz# Optional: Validate the hash $ echo "0dbc9bf5a58620fc52cb6cc0448abcca964a8d74b5f39773b7afcad9ab691e19  actions-runner-linux-x64-2.323.0.tar.gz" | shasum -a 256 -c# Extract the installer $ tar xzf ./actions-runner-linux-x64-2.323.0.tar.gz Configure # Create the runner and start the configuration experience $ ./config.sh --url https://github.com/kfhunter1/upgraded-octo-dollop --token BQV6PT6KVF5MVE5ARD6S6PTIBOMYS# Last step, run it! $ ./run.sh Using your self-hosted runner # Use this YAML in your workflow file for each job runs-on: self-hosteactions-runner-linux-x64-2.323.0.tar.gzhttps://github.com/actions/runner/releases/download/v2.323.0/actions-runner-linux-x64-2.323.0.tar.gz#https://github.com/kfhunter1/upgraded-octo-dollop256Execute::Project 222actions-runner-linux-x64-2.323.0.tar.gzhttps://github.com/actions/runner/releases/download/v2.323.0/actions-runner-linux-x64-2.323.0.tar.gz#256https://github.com/kfhunter1/upgraded-octo-dollophttps://github.com/actions/runner/releases/download/v2.323.0/actions-runner-linux-x64-2.323.0.tar.gz#https://github.com/kfhunter1/upgraded-octo-dollop256Execute::ProjectCreate a folder
$ mkdir actions-runner && cd actions-runner# Download the latest runner package
$ curl -o actions-runner-linux-x64-2.323.0.tar.gz -L https://github.com/actions/runner/releases/download/v2.323.0/actions-runner-linux-x64-2.323.0.tar.gz# Optional: Validate the hash
$ echo "0dbc9bf5a58620fc52cb6cc0448abcca964a8d74b5f39773b7afcad9ab691e19  actions-runner-linux-x64-2.323.0.tar.gz" | shasum -a 256 -c# Extract the installer
$ tar xzf ./actions-runner-linux-x64-2.323.0.tar.gz
Configure
# Create the runner and start the configuration experience
$ ./config.sh --url https://github.com/kfhunter1/upgraded-octo-dollop --token BQV6PT6KVF5MVE5ARD6S6PTIBOMYS# Last step, run it!
$ ./run.sh
Using your self-hosted runner
# Use this YAML in your workflow file for each job
runs-on: self-hostehttps://github.com/devcontainers/feature-starterExecute::Project 222
