# Environment

I'm using the pyenv tool for Python version control.
I recommend doing the same, I used Python version 3.7.10

```
pyenv install 3.7.10
```
<br>

After install, you can set this version as default:
```
pyenv global 3.7.10
```
<br>

Now we set a virtual env using the following command:

```
python3 venv -m .venv
```

At last, im using HTTPie, to make the requests.
But you can use whatever you want.. (Postma, curl ...).

To install the HTTPie:

```
sudo apt-get update; sudo apt-get install httpie
```