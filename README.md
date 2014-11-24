Standards
=========

Our web standards

# Table of Contents
1. [File Management](#file-management)
    * [Dropbox](#dropbox)
        * [Dropbox Naming Standards](#dropbox-naming-standards)
        * [Dropbox Project Structure](#dropbox-project-structure)

# File Management
All web projects MUST be kept on [Dropbox](#dropbox) and they MUST follow the correct [dropbox naming standards](#dropbox-naming-standards) AND [dropbox project strcuture](#dropbox-project-structure).

## Dropbox

### Dropbox Naming Standards
When creating a new directory OR file their names MUST:
* be all lowercase
* use hyphens as separators
    
Example:
```
dropbox-example
dropbox-example.file
```
   
To support custom ordering a directory name CAN:
* be prefixed with an underscore
* be prefixed with 2 numerical digits
     
Example:
```
_dropbox-example
01-dropbox-example
```

### Dropbox Project Structure
The project structure MUST include the following in this order:

Job Number - Project Name

1. Client Assets
2. Planning
3. Wireframes
4. Styles
5. Development
6. Testing
7. Documentation
    
Example:
```
├── ab01-dropbox-example
│   ├── 01-client-assets
│   ├── 02-planning
│   ├── 03-wireframes
│   ├── 04-styles
│   ├── 05-development
│   ├── 06-testing
│   └── 07-documentation
```

#### Client Assets
There MUST be a directory named Archive AND it MUST be the first directory.
Optionally there CAN be a directory that can be shared with the client which MUST be named MVP Shared Assets.
Files AND directories inside of the MVP Shared Assets folder may OR may not follow the [dropbox naming standards](#dropbox-naming-standards).

Example:
```
├── 01-client-assets
│   ├── _archive
│   └── _mvp-shared-assets
```
