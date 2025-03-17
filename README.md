# Talk
Talk is a very simple GUI text communication software.
> [!WARNING]
> Messages are **not encrypted** and can be **easily tampered**.

## Usage
1. Download the suitable version for your computer.
2. Run it.

## TODO
- [x] Finish P2P server
- [ ] Finish P2P client
- [ ] Finish Group chat server
- [ ] Finish Group chat client
- [ ] Add SSL support
- [ ] Add i18n support

## How to build it (Windows)
1. [Download and install Python](https://www.python.org/downloads/windows/).
> [!IMPORTANT]
> Don't forget to check tkinter and pip support.

2. Run `pip install pyinstaller` in cmd.
3. Download zip.
4. Decompress the zip.
5. `cd` into the decompressed folder.
6. Run `cd src`.
7. Run `pyinstaller -F` on each file you want to build.
8. Done.

## How to build it (Distributions based on Debian Linux)
1. Get a root shell.
> [!WARNING]
> Please **don't** use `fakeroot`! The following steps need **real** root permission to manipulate files only root can access!

2. Run `apt install python3-full -y`
3. Run `apt install python3-pyinstaller -y`
4. Download zip.
5. Decompress the zip.
6. `cd` into the decompressed folder.
7. Run `cd src`.
8. Run `pyinstaller -F` on each file you want to build.
9. Done.

## How to build it (Distributions based on Redhat Linux)
1. Get a root shell.
> [!WARNING]
> Please **don't** use `fakeroot`! The following steps need **real** root permission to manipulate files only root can access!

2. Run `yum install python3-full -y`
3. Run `yum install python3-pyinstaller -y`
4. Download zip.
5. Decompress the zip.
6. `cd` into the decompressed folder.
7. Run `cd src`.
8. Run `pyinstaller -F` on each file you want to build.
9. Done.

## License
CC0 1.0 Universal

## EULA (End User License Agreement)
By using this software, you agree to the following statement:
The author([g1thubhack3r](https://github.com/g1thubhack3r)) isn't responsible for anything this software([Talk](https://github.com/g1thubhack3r/Talk)) caused.
