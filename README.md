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

#### Planning
There MUST be a directory named Archive AND it MUST be the first directory.
Any files contained in subsequent folders SHOULD be the most recent versions. 
All older versions SHOULD be moved to the Archive folder regularly.

Example:
```
├── 02-planning
│   ├── _archive
│   ├── 01-scoping
│   ├── 02-estimate
│   ├── 03-needs-analysis
│   ├── 04-creative-brief
│   ├── 05-site-map
│   └── 06-resources
```

#### Wireframes
There MUST be a directory for EACH page.
There MUST be a directory named Archive in EACH page directory AND it MUST be the first directory. 
There MUST be a directory named Screens in EACH page directory AND if MUST be the second directory.
Images inside the Screens directory SHOULD be the most updated version of the wireframe. 
File names MUST use the following structure: jobnumber-description-version-extension

Example:
```
├── 03-wireframes
│   ├── 01-homepage
│   │   ├── _archive
│   │   ├── _screens
│   │   ├── v1
│   │   │   ├──ab01-homepage-v1-1.psd
│   │   │   └──ab01-homepage-v1-2.psd
│   │   ├── v2
│   │   │   └──ab01-homepage-v2-1.psd
│   │   └── v3
│   ├── 02-sub-page1
│   │   ├── _archive
│   │   ├── _screens
│   │   ├── v1
│   │   │   └──ab01-sub-page1-v1-1.psd
│   │   ├── v2
│   │   └── v3
│   └── 02-sub-page2
│   │   ├── _archive
│   │   ├── _screens
│   │   ├── v1
│   │   │   └──ab01-sub-page2-v1-1.psd
│   │   ├── v2
│   │   └── v3
```

#### Styles

Example:
```
├── 04-styles
```

#### Development

Example:
```
├── 05-development
```

#### Testing

Example:
```
├── 06-testing
```

#### Documentation

Example:
```
├── 07-documentation
```