# SRM comand to your bash

At first open bash and:

```sh
cd ~
```

```sh
git clone https://github.com/AnastasiiaUsik/gitflow
```

Now you need to repeat one command after another:

```sh
cd ~/gitflow
```

```sh
chmod +x srm
```

```sh
mkdir ~/bin
```

```sh
cd ~
```

Open .bash_profile with:

```sh
nano .bash_profile
```

Add this line and save:

```sh
export PATH="${PATH}:~/bin"
```

Reconnect bash, after try `echo $PATH` and you will see `~/bin`.
Now write to terminal these commands:

```sh
cd ~/gitflow
```

```sh
cp srm ~/bin/srm
```


Done! Now you can use the command `srm`. It will save files you delete to RECYCLE and automate delete after 7 days.
