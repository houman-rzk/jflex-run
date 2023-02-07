# jflex-run
A script that automates working with jflex and java-cup through the CLI.
Running the script will compile both the jflex lexical and java-cup syntactical analyzers before feeding them the source file to be analyzed.

### Dependencies
- jflex
- java-cup

### Installation
Copy jflex-run to your PATH and make it executable.


### Usage
`jflex-run [Options]`

#### Options
- `-h`          Displays the help message and exits.
- `-j <file>`   Use <file> as jflex lexical specification file.
- `-s <file>`   Use <file> as source code file.
- `-c <file>`   (Optional) Use <file> as cup specification file.
- `-l <dir>`    (Optional) Path to library directory. Multiple library directories can be specified by separating them with ':' (as in `<dir>:<dir>`).

### Notes
To use java-cup you must have the 'java-cup-<version>.jar' and java-cup-<version>-runtime.jar' files in your /path/to/jflex/lib/ directory (you can specify this directory by setting the 'JFLEXLIB' variable or by using the '-l' option.

### Help
Check the source code, it's the best documentation
