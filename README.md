# Atom dbt package

Provides syntax highlighting and a number of snippets for dbt-flavored SQL, YAML and Markdown files in Atom.

## Usage
* Highlighting: SQL, YAML and Markdown files will be highlighted automatically
* Snippets: To use snippets, type one of the prefixes (e.g. `macro`), and then `tab`.
* Commenting: This package overrides the default comment behavior of each language to instead use Jinja comments. Use `Cmd + /` to comment out code.


## How use own keywords using atom in developer mode

Got inspiration from here: https://discuss.atom.io/t/how-to-change-an-existing-package/4349/5
> What I do is, I first clone the git project, then I uninstall the package,
and go to my new git cloned package and run this command `apm link --dev` that
creates a symbolic link into `~/.atom/dev/packages` then I open Atom in dev mode from my package directory `atom --dev` then I can start making changes to the package and **View -> Reload** to see my changes.
