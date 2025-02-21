
# Reference of theme options

The following theme-specific options are available via `html_theme_options`.

```{admonition} See the PyData Theme as well
These are **in addition to** all of the {external:doc}`options available in the PyData Sphinx Theme <user_guide/index>`.
```

```{list-table}
:widths: 10 5 40
:header-rows: 1
* - Key
  - Type
  - Description
* - `path_to_docs`
  - string
  - Path to the documentation, relative to the repository root (e.g. `docs/`). See [](customize:source-files).
* - `repository_url`
  - string
  - URL of the repository for the documentation (e.g. the GitHub repository URL). See [](source-files:repository).
* - `repository_branch`
  - string
  - Branch of the repository for the documentation (e.g., `master`, `main`, `docs`). See [](source-files:repository).
* - `use_issues_button`
  - bool
  - Add an button in the header with a link to issues for the repository (used in conjunction with `repository_url` and `repository_branch`). See  [](source-files:repository).
* - `use_download_button`
  - bool
  - Add a button in the header to download the source file of the page. See [](customize:source-files).
* - `use_fullscreen_button`
  - bool
  - Add a button in the header to trigger full-screen mode.
* - `use_repository_button`
  - bool
  - Add a button in the header that links to the repository of the documentation.See [](source-files:repository).
* - `launch_buttons`
  - bool
  - Include Binder launch buttons for pages that were built from Jupyter Notebooks. See [](customize:launch).
* - `home_page_in_toc`
  - bool
  - Whether to put the home page in the Navigation Bar (at the top). See [](sidebar-primary:home-page).
* - `show_navbar_depth`
  - int
  - Show children in the navigation bar down to the depth listed here. See [](sidebar:navbar-depth).
* - `extra_footer`
  - str
  - Extra HTML to add in the footer of each page.
* - `toc_title`
  - str
  - The text to be displayed with the in-page TOC (`Contents` is default)
```
