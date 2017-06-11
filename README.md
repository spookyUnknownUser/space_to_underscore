# Recursively replace underscores with spaces in file and directory names

A safe solution to recursively replace underscores with spaces in file and directory names starting from the current directory.

## Example
```
tree
.
|-- a_dir
|   `-- file_with_underscores.txt
`-- b_dir
    |-- another_file_with_underscores.txt
    `-- yet_another_file_with_underscores.pdf
```

becomes:
```
tree
.
|-- a dir
|   `-- file with underscores.txt
`-- b dir
    |-- another file with underscores.txt
    `-- yet another file with underscores.pdf
```

## Usage

Give execute permissions:
```
chmod +x underscoreToSpace.sh
```

Go to needed directory:
```
cd /home/user/example
```

Run the space_to_underscore.sh which placed in user home directory:
```
~/underscoreToSpace.sh
```

## License

This script is licensed under the [GNU General Public License, version 3 (GPLv3)](http://www.gnu.org/licenses/gpl-3.0.html) and is distributed free of charge.

Commercial licensing (e.g. for projects that can’t use an open-source license) is available upon request.


## Author

Arthur Garegnyan

* Email: arthurgareginyan@gmail.com

* GitHub: [https://github.com/ArthurGareginyan/](https://github.com/ArthurGareginyan/)

* Website: [http://www.arthurgareginyan.com](http://www.arthurgareginyan.com)

* Donation: [http://www.arthurgareginyan.com/donate.html](http://www.arthurgareginyan.com/donate.html)
