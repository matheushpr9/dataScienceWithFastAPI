# Environment

I'm using the pyenv tool for Python version control.
I recommend doing the same, I used Python version 3.7.10

```bash
#!/bin/bash
pyenv install 3.7.10
```

&nbsp;

After install, you can set this version as default:

```bash

pyenv global 3.7.10

```

&nbsp;

Now we set a virtual env using the following command:

```bash

python3 venv -m .venv

```

&nbsp;

At last, im using HTTPie, to make the requests.
But you can use whatever you want.. (Postman, curl ...).

To install the HTTPie:

```bash
sudo apt-get update; sudo apt-get install httpie
```
