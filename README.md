# CaSILE Template

This a **template** repository for starting new [CaSILE][] based projects.
It is designed to be as minimal as possible to get get you started.

1. Start a new project with ["Use this template"][use-template] ([docs][template-docs]).
   Alternatively if not using GitHub, clone this repository yourself or download and extract the [ZIP file][master.zip] then `git init` your own repository.
2. Remove (or rewrite) this `README.md` file and update the `LICENSE` file to suit your project.
3. Rename the files `my_book.md` and `my_book.yml` to a name suitable to your project.
4. Replace and extend the values in `casile.mk` to suit your project.
5. Run `casile setup`.

These files and values should be enough to get the ball rolling.
You should now be able to run `casile make`.

Perhaps the most useful addition for most projects will be to add a remote CI configuration.
Because not all projects will want this and there are many options for this that will need to be tailored to your situation no CI configuration is included in this template.
See the [CaSILE][] documentation for details.

See the [CaSILE Demos repository][demos] for more advanced usage working examples.

  [CaSILE]: https://github.com/sile-typesetter/casile
  [demos]: https://github.com/sile-typesetter/casile-demos
  [master.zip]: https://github.com/sile-typesetter/casile-template/archive/master.zip
  [template-docs]: https://docs.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template
  [use-template]: https://github.com/sile-typesetter/casile-template/generate
