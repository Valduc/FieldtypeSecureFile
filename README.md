# FieldtypeSecureFile

FieldtypeSecureFile is a ProcessWire FieldType module that allows you to store files in a customized location, such as outside the web root, for enhanced security.

## Features

- Store files securely outside the web root
- Customizable storage location
- Integration with ProcessWire's file handling

## Installation

1. Download the module and place it in the `site/modules/FieldtypeSecureFile` directory of your ProcessWire installation.
2. In the ProcessWire admin, go to Modules > Refresh.
3. Install the `FieldtypeSecureFile` module.

## Usage

1. Add a new field of type `FieldtypeSecureFile` to your template.
2. Configure the storage location for the field in the field settings.
3. Use the field in your templates to upload and manage secure files.

## Hooks

The module provides hooks for handling file events:

- fileReplaced(HookEvent $event): Triggered when a file is replaced.
- deleteFiles(HookEvent $event): Triggered when a file is deleted.

## Debugging

The module includes debugging lines that can be uncommented to log information about file operations. These logs are saved to the secure-file-log.

## Author

Originally developed by Stefan Wanzenried. Adapted and updated by Luc Vandamme.