# Archive Layout
One of the reasons things are taking a bit of time is the categorizing, sorting and processing files.

## Old Layout
**Applications** and things that are not considered games, live inside one folder.  
**Games** and things that are not considered applications or misc of applications, live inside one folder.  
**Documents** are all filed under one folder, regardless of the parent (Application, Game).  
**Screenshots** are all filed under one folder, regardless of the parent (Application, Game).

This is not practical by any means, there's no knowing which file is what except for guessing from the filename itself. As the amount of files increase, so does the mess on the current website.

## New Layout
For purposes of sanity and means to navigate more easily, the new archive (with all the old files) currently has the following layout.  
Some applications or games are without subcategory and subgenre respectively, and are therefore placed in the root of the category or genre.

Subcategories as well as subgenres are easily identified by an underscore before the sub-cat/genre

```bash
Applications/
└── Category/
    └── _Subcategory/
        └── Software_Title/
            ├── Documents/
            │   ├ file.extension
            │   └ ...
            ├── Media/
            │   ├ file.extension
            │   └ ... 
            └── Version/
                └── Version.Number/
                    ├ file.extension
                    └ ...
Games/
└── Genre/
    └── _Subgenre/
        └── Software_Title/
            ├── Documents/
            │   ├ file.extension
            │   └ ...
            ├── Media/
            │   ├ file.extension
            │   └ ... 
            └── Version/
                └── Version.Number/
                    ├ file.extension
                    └ ...
```
