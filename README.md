name: Your CICD Pipeline Name
on: [push]
jobs:
  myjob:
    runs-on: ubuntu-latest
    steps:
    - uses: actions/checkout@v2
    - name: Run a one-line script
      run: echo Hello, World!!