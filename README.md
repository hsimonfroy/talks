# Talks
Slides for talks.

## Creating a new Presentation:

  - Create a new branch, make a copy of `template`, and `cd` there
    ```shell
    $ cp -a template/ new_pres/
    ```
  - git submodule current version of reveal.js
    ```shell
    $ git submodule add https://github.com/EiffL/reveal.js.git
    $ cd reveal.js
    $ git submodule update --init --recursive
    ```
  - copy `package.json` and `gulpfile.js` from  the `reveal.js` folder to the talk directory
  - Update/install npm modules to make sure it  works with this version:
    ```shell
    $ npm install
    ```
  - Start the server:
    ```shell
    $ npm start
    ```

