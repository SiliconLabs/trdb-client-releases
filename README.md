# trdb-client-releases
Contains compiled releases for the Trip Report Database client applications. All source code is contained in a separate Stash repository.

### Platforms
Releases will be compiled for the following platforms:

* Windows ia32
* Windows x64
* MacOS
* Web/Salesforce.com

### Releases
Compiled assets for each platform are attached using GitHub Releases.

### Automatic Updates
Desktop clients can be updated automatically. Each release will contain the assets required for Electron's `autoUpdater` ([docs](http://electron.atom.io/docs/api/auto-updater/)) module. A [Nuts](https://github.com/GitbookIO/nuts) instance is used to serve these assets directly to clients.
