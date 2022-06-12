<!-- <div align="center" id="top"> 
  <img src="./.github/app.gif" alt="Linux Guide" />

  &#xa0;

  <a href="https://linuxguide.netlify.app">Demo</a>
</div> -->

# full linux guide #

Status

<!-- <h4 align="center"> 
	🚧  Linux Guide 🚀 Under construction...  🚧
</h4>  -->

<h4 align="center"> 
	🚧  Under construction... 🚧
</h4>

<hr>

## About ##
Documents, files, permissions, networking and packages;

## Summary ##
1. [Navigation & Basics](#navigation&basics)
2. [Permissions](#permissions)

## Content ##
<!-- Navigation & Basics -->
<details id="navigation&basics" open>
  <summary style="font-size: 18px;">Navigation & basics</summary>

  - `pwd` current path;
  - `cd [path]` for navigating between files;
  - `ls [?path]<?filename>` or `dir [?path]<?filename>` lists files and documents;
  - `touch [?path]<document-name>` to create empty document;
  - `nano [?path]<?document-name>` unix text editor to write or alter a document;
  - `cat [?path]<document-name>` print document content;
  - `mkdir [?path]<document-name>` to create empty file;
  - `rmdir [?path]<filename>` to remove empty file;
  - `rm` for remove
    - `-r` remove directories and their conts recursively;
    - `-f` ignore nonexistent files and arguments, never prompt;
  - `mv [souce]<filename> [destination]<?newFilename>` move or rename both files and documents;
  - `cp [source] [destination]` copy document or file;
  - `whoami` prints current user;
  - `clear` cleans the terminal;
  - `sudo` abbreviation for *SuperUser DO*, executes the following command in superuser mode;
  - `su` change root user shell;
    - `exit` to leave root user shell and return to the previous user;
  <br>

  > obs:. For ? before command parameter, such parameter should be considered optional, note that case such parameter do not be passed the command will assume it as default value. e.g.: for document and file editing commands in case the parameter `<path>` is not passed, the command will assume its value as the current path;

</details>

<!-- Permissions -->
<details id="permissions" open>
  <summary style="font-size: 18px;">Permissions</summary>

  - `chmod` alter document/file permissions;
  <table>
    <tr>
      <th>owner</th>
      <th>group</th>
      <th>other</th>
    </tr>
    <tr>
      <th>0</th>
      <th>0</th>
      <th>0</th>
    </tr>
  </table>

  <table>
    <thead>
      <tr>
        <th>Permission</th>
        <th>Number</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <th>Read (r)</th>
        <th>4</th>
      </tr>
      <tr>
        <th>Write (w)</th>
        <th>2</th>
      </tr>
      <tr>
        <th>Execute (x)</th>
        <th>1</th>
      </tr>
    </tbody>
  </table>

  ```bash
  $ chmod 751 myfile
  ```
</details>



