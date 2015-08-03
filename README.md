# Wedding Site

## Creating new section

* Create a new markdown file in `./sections/` directory with the following front matter:
    ```
    ---
    layout: content
    name: <name of section>
    ---
    ```
* Add a hash to the `sections` in `_config.yml` like so:
    ```
    - name: <name of section # should match the above file>
      menu: <true|false> # should this section appear in the top menu?
      title: <nice name for the section>
    ```

# TODO

* Content - check it all with Holly
* form
    * fields
        * Name
        * email
        * address....
        * comments (eg are you likely to move between now & then)
    * Zapier
