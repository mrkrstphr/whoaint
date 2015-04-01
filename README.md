# whoaint
> I just want to know if the domain name is available, yo

A simple little bash script to tell you whether or not a domain name is available, 
harnessing the raw power of `whois`.

For people like me, who buy domains frequently and do nothing with them because Internet.

## Installation

Put dat `whoaint` in some directory within your `PATH`

```bash
echo $PATH
```

I humbly suggest `~/bin` as a good home. Make sure that directory is in your `PATH`.

```bash
echo 'export $PATH="~/bin:$PATH"' >> ~/.bashrc
```

Or:

```bash
echo 'export $PATH="~/bin:$PATH"' >> ~/.zshrc
```

Or whatever kind of crazy setup you have going.

## Usage

```bash
$ whoaint microsoft.com

Domain microsoft.com is taken. Prolly squatters...
```
