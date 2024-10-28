# Blossom plugins

This repo contains all blossom plugins. If you want to install one of these plugins, download that certain plugin from the plugins folder and then put it into your plugins folder in your blossom application. You can also check that you have all dependencies and the required versions by doing a command with the base version or via manually checking the plugin.json files in each plugin you want.

## Features included with plugins

### PowerRename

A plugin that helps you rename a file to a better suitable name based on my styleguide.

### NeuroSort

A plugin helping you to sort files based on their connection to other files. This could for example utilize metadata.

### LexiSort

A plugin helping you to sort files based on a lexicon or dictionary you created.

### ArchiFile

A plugin with comprehensive archiving functionality for archiving files. This could be used together with `FileSense` to automatically archive files that seem to not have been used in a long time.

> [!IMPORTANT]
> Requires FileSense

### CogniPulse

A plugin that organizes files dynamically based on usage. This could be set up to utilize a folder structure based on usage.

### ChronoFile

A plugin that handles metadata related to time, for example when a file was created and last modified. This plugin is basic but not in the core app since some might not want to share that due to privacy reasons.

### SizeInsight

A plugin that handles metadata related to data size and how it changed over the last modification.

### UsageStats

A plugin that displays the size of files and folders and how it has changed over time. It also maps out the distribution of file types across directories, helping users understand their file composition.

> [!IMPORTANT]
> Requires SizeInsight

### FileSense

A plugin that determines whether a file is in use or it should be archived based on a specific algorithm and data gathered from `ChronoFile`.

> [!IMPORTANT]
> Requires ChronoFile

### FileMinder

A plugin that could remind users of where a file is located.

### Medula

A plugin that could create reminders and remind users about activities.

### Activities

A plugin that could create to-dos. This plugin could work better with `Medula`.

> [!IMPORTANT]
> Requires Medula

### StabiliFile

Creates systematic backups of the whole structure so if something goes wrong, all or most of the content could be retrieved. This works as a backup system and could be great if you later want to switch to another device. This also stores your latest config file.

### FileSync

A plugin which helps synchronizing files across devices.

### SecureVault

A plugin which helps secure your folders and data. This will automatically password protect your information including your config file, backups and more.

### AccessControl

A plugin that allows users to set access permissions for individual files and folders. Supports role-based access control to manage permissions for different user roles.

> [!IMPORTANT]
> Requires SecureVault

### SecurityMonitoring

A plugin that saves how many times the files/folders have been opened and what time to let users check if any unauthorized users have checked their files while they have been gone.

> [!IMPORTANT]
> Requires SecureVault

### DupliCheck

A plugin that helps users check for duplicate files.

> [!IMPORTANT]
> Requires ChronoFile, UsageStats, SizeInsight

### GitLabMirroring

A plugin that lets you always have the latest version of a GitLab repository available locally. This will download the latest version of the repository but _NOT_ update the repository based on local changes.

### GitHubMirroring

A plugin that lets you always have the latest version of a GitHub repository available locally. This will download the latest version of the repository but _NOT_ update the repository based on local changes.
