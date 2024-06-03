# `tmp-box` File Manager

`tmp-box` is a file management tool that simplifies working with files and templates. With an easy-to-use command-line interface, it allows users to visualize, manage, and control file structures efficiently.

## Features

- Visualize files and directories with ease.
- Manage templates through a simple interface.
- Support for various file types including `.txt`, `.json`, `.py`, `.md`, and `.pyc`.
- Easily add, update, and delete template aliases.

## Installation

To install `tmp-box`, run the following command:

```bash
pip install tmp_box
```

## Usage

Below are some of the commands you can use with `tmp-box`:

To add a new template:

```
tmp-box add --path <path-to-directory> --name <alias>
```

To delete a template by alias:

```
tmp-box del --name <alias>
```

To view the latest template:

```
tmp-box last
```

For more detailed usage, please refer to the command help within the application.



## Contributing

Contributions to `tmp-box` are welcome! Please read our contributing guidelines before submitting pull requests.

## License

This project is licensed under the MIT License.