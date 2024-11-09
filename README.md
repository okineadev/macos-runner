# 🏃‍♂️‍➡️ macos-runner

This is a repository with **GitHub Action** that you can use to connect to a GitHub-hosted **macOS** machine to test your applications over **SSH**.

Thanks to this, you do not need to specially buy a MacBook in order to check whether your program will work on it

## ⚠️ Rules of use

1. **Do not** abuse the machines (abusing free resources is bad)
2. **Do not** use it for long-term tasks (it is not a dedicated server specifically for you)
3. **Do not** use this runner for **mining**, **DDoS attacks**, activities that are against the **GitHub** policies or any other illegal activities

Remember that the runners is **free** for any open-source projects, so please respect the rules of use

## 🚀 How to use

1. Fork this repository
2. Go to the **Actions** tab
3. Click on the **macos-runner** workflow
4. Click on the **Run workflow** button
5. Select the version of the **macOS** you want to use (`macos-latest` by default), read about these versions [here](https://docs.github.com/en/actions/using-github-hosted-runners/using-github-hosted-runners/about-github-hosted-runners#standard-github-hosted-runners-for-public-repositories)
6. Click on the **Run workflow** button
7. Wait for the **tmate** session to be established, when it is established, the logs will show a command to connect via SSH or a link to a web terminal
8. Connect

---

Fewer bugs and happy coding! 😄
