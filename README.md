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

<h2>License</h2>
<a href="http://www.apache.org/licenses/LICENSE-2.0.html">Apache License 2.0</a>
