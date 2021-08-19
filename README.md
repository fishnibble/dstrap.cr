# dstrap

`dstrap` is a simple script made to get the most useful information about your current working directory. Made with Crystal for Linux systems, it's the perfect supplement to commands like `ls -a` now acepting ARGS!.

### Installation:

To install and build the latest version of `dstrap`, navigate to your home directory and create a `bin/` folder:

```
cd ~
mkdir -p bin && cd bin
```

Move to the bin folder and copy the following installation script:

```bash
wget -O dstrap.cr https://raw.githubusercontent.com/fishnibble/dstrap.cr/main/dstrap.cr
crystal build dstrap.cr -o dstrap --release --no-debug --progress
rm dstrap.cr && chmod +x ./dstrap
```

Then add the compiled exectable to $PATH:

```
export PATH="$PATH:/home/$USER/bin"
```

And that's all! Call the command `dstrap` from anywhere and enjoy! 🎉

![image](https://storage.googleapis.com/replit/images/1621009367878_bd4e8ba7dbdd96de114354dce93bea2c.png)
