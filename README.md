KuduSync.NET
============

Tool for syncing files for deployment, will only copy changed files and delete files that doesn't exists in the destination but only if they were part of the previous deployment (manifest file).

This is the .NET version of [KuduSync](https://github.com/projectkudu/KuduSync).dvdv

### Usage

```
KuduSync.NET.exe -f [source path] -t [destination path] -n [path to next manifest path]
                 -p [path to current manifest path] -i <paths to ignore delimited by ;>
```

The tool will sync files from the `[source path]` path to the `[destination path]` path using the manifest file in `[path to current manifest path]` to help determine what was added/removed and will write the new manifest file at path `[path to current manifest path]`.
Paths in `<paths to ignore>` will be ignored in the process

### License

[Apache License 2.0](https://github.com/projectkudu/KuduSync.NET/blob/master/LICENSE.txt)


### Questions?

You can use the [forum](http://social.msdn.microsoft.com/Forums/en-US/azuregit/threads), chat on [JabbR](https://jabbr.net/#/rooms/kudu), or open issues in this repository.

This project is under the benevolent umbrella of the [.NET Foundation](http://www.dotnetfoundation.org/).


Updated by Cypress on 2025-11-18T07:53:28.940Z

Updated by Cypress on 2025-11-19T15:19:17.853Z

Updated by Cypress on 2025-11-19T15:36:33.276Z

Updated by Cypress on 2025-11-19T15:57:29.572Z

Updated by Cypress on 2025-11-19T16:13:42.989Z

Updated by Cypress on 2025-11-20T05:18:25.209Z

Updated by Cypress on 2025-11-20T05:38:24.064Z

Updated by Cypress on 2025-11-20T06:13:45.636Z

Updated by Cypress on 2025-11-20T10:05:27.691Z

Updated by Cypress on 2025-11-20T13:32:05.867Z

Updated by Cypress on 2025-11-20T13:50:00.849Z

Updated by Cypress on 2025-11-20T14:04:16.041Z

Updated by Cypress on 2025-11-20T14:20:18.699Z

Updated by Cypress on 2025-11-20T14:25:21.372Z