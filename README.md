# Hugo theme take notes

This theme is mainly used for taking notes with AsciiDoctor and can be easily navigated in different chapters.

Asciidoctor is more expressive than Markdown. For example, it has easier diagrams integration and more powerful tables.

Example website can be found [here](https://github.com/shichaoxia/hugo-theme-take-notes-example). [Preview](https://hugo-theme-take-notes-example.pages.dev/).

![screenshot](https://github.com/shichaoxia/hugo-theme-take-notes/blob/main/images/screenshot.jpg)

## Usage

1. Initialize the hugo module system in your site project:
   ```console
   hugo mod init github.com/<your_user>/<your_project>
   ```
2. Import the theme in `config.toml`:
   ```toml
   [module]
   [[module.imports]]
   path = 'github.com/spf13/hyde'  
   ```
3. Update modules
   ```console
   hugo mod get -u
   ```
