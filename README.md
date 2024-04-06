# Update VSCode Version automatically in Ubuntu/Debian

<p align="center">
    <a href="https://ubuntu.com/" alt="Ubuntu">
        <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white" /></a>
    <a href="https://www.debian.org/" alt="Debian">
        <img src="https://img.shields.io/badge/Debian-A81D33?style=flat&logo=debian&logoColor=white" /></a>
    <a href="https://code.visualstudio.com/" alt="Visual Studio Code">
        <img src="https://img.shields.io/badge/Visual%20Studio%20Code-007ACC?style=flat&logo=visual-studio-code&logoColor=white" /></a>
</p>

<pre>
            _  (`-') _(`-')    (`-')  _ (`-')      (`-')  _         (`-') (`-').->                     _(`-')    (`-')  _
     .->    \-.(OO )( (OO ).-> (OO ).-/ ( OO).->   ( OO).-/        _(OO ) ( OO)_   _             .->  ( (OO ).-> ( OO).-/
,--.(,--.   _.'    \ \    .'_  / ,---.  /    '._  (,------.   ,--.(_/,-.\(_)--\_)  \-,-----.(`-')----. \    .'_ (,------.
|  | |(`-')(_...--'' '`'-..__) | \ /`.\ |'--...__) |  .---'   \   \ / (_//    _ /   |  .--./( OO).-.  ''`'-..__) |  .---'
|  | |(OO )|  |_.' | |  |  ' | '-'|_.' |`--.  .--'(|  '--.     \   /   / \_..`--.  /_) (`-')( _) | |  ||  |  ' |(|  '--. 
|  | | |  \|  .___.' |  |  / :(|  .-.  |   |  |    |  .--'    _ \     /_).-._)   \ ||  |OO ) \|  |)|  ||  |  / : |  .--' 
\  '-'(_ .'|  |      |  '-'  / |  | |  |   |  |    |  `---.   \-'\   /   \       /(_'  '--'\  '  '-'  '|  '-'  / |  `---.
 `-----'   `--'      `------'  `--' `--'   `--'    `------'       `-'     `-----'    `-----'   `-----' `------'  `------'
                                (`-') (`-')  _   (`-')  (`-').->  _                <-. (`-')_  
                                _(OO ) ( OO).-/<-.(OO )  ( OO)_   (_)         .->      \( OO) ) 
                            ,--.(_/,-.\(,------.,------,)(_)--\_)  ,-(`-')(`-')----. ,--./ ,--/  
                            \   \ / (_/ |  .---'|   /`. '/    _ /  | ( OO)( OO).-.  '|   \ |  |  
                            \   /   / (|  '--. |  |_.' |\_..`--.  |  |  )( _) | |  ||  . '|  |) 
                            _ \     /_) |  .--' |  .   .'.-._)   \(|  |_/  \|  |)|  ||  |\    | 
                            \-'\   /    |  `---.|  |\  \ \       / |  |'->  '  '-'  '|  | \   |  
                                `-'     `------'`--' '--' `-----'  `--'      `-----' `--'  `--' 
</pre>

## :scroll: Introduction

This script will help you to update your Visual Studio Code version automatically in Ubuntu/Debian with one cli command.

## :hammer_and_wrench: Prerequisites

This script requires the following prerequisites:

- sudo privileges.
- [wget](https://www.gnu.org/software/wget/) installed on your system.

## :rocket: Installation

1. Clone the repository:

```bash
git clone https://github.com/AlejandroPqLz/auto-update-vscode-ubuntu.git
```
```bash
cd auto-update-vscode-ubuntu
```

2. Add `.sh` file to ~/.local/bin directory:

```bash
sudo cp update-vscode.sh ~/.local/bin/update-vscode
```
> <span style="color: red; font-size: 1.5em;">&#9888;</span> **WARNING:** If the directory `~/.local/bin` does not exist, just create it:
> ```bash
> mkdir -p ~/.local/bin
> ```

3. Add ~/.local/bin to your $PATH:

```bash
echo 'export PATH="$HOME/.local/bin:$PATH"' >> ~/.bashrc
```

4. Add execution permissions to the file:

```bash
sudo chmod +x ~/.local/bin/update-vscode
```

5. Reload your bashrc:

```bash
source ~/.bashrc
```

## :gear: Usage

To update your Visual Studio Code version, you just need to run the following command (the name of the .sh file):

```bash
auto-update-vscode
```

## :warning: Important

- This script will remove the previous version of Visual Studio Code and install the latest version.
- You could choose any other location to add the script, just make sure to add the location to your $PATH.

## :seedling: Contributing

If you wish to make contributions to this project, please initiate the process by opening an issue or submitting a pull request that encapsulates your proposed modifications.

> 1. Fork the Project
> 2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
> 3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
> 4. Push to the Branch (`git push origin feature/AmazingFeature`)
> 5. Open a Pull Request
> 6. Wait for the PR to be reviewed
> 7. If it's approved, the changes will be merged
> 8. Done!

## :newspaper_roll: License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details.

## :busts_in_silhouette: Contact

Should you have any inquiries or require assistance, please do not hesitate to contact [Alejandro Pequeño Lizcano](pq.lz.alejandro@gmail.com).
