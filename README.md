# Mibew Tray Notification plugin

Plugin notifies a Mibew operator about new visitors requested a chat in the Windows system tray.

<h2>Installation</h2>

Get the archive with the plugin sources. At the moment the only option is to build the plugin from sources.

    Untar/unzip the plugin's archive.

Put files of the plugins to the <Mibew root>/plugins folder.
(optional) Add plugins configs to "plugins" structure in "<Mibew root>/configs/config.yml". If the "plugins" stucture looks like plugins: [] it will become:

    plugins:
        "AARInnovations:TrayNotification": # Plugin's configurations are described below
            new_thread: true

Navigate to "<Mibew Base URL>/operator/plugin" page and enable the plugin.

<h2>Build from sources</h2>

There are several actions one should do before use the latest version of the plugin from the repository:

    Obtain a copy of the repository using git clone, download button, or another way.
    Install node.js and npm.
    Install Gulp.
    Install npm dependencies using npm install.
    Run Gulp to build the sources using gulp default.

Finally .tar.gz and .zip archives of the ready-to-use Plugin will be available in release directory.

<h2>License</h2>
<a href="http://www.apache.org/licenses/LICENSE-2.0.html">Apache License 2.0</a>
