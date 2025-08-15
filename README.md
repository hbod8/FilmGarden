# FilmGarden
A web garden for film tips and knowledge. A Sprout of Seattle Film Club.

## Contributing Notes

To add notes, make a `.md` file in the `content/` folder. Thats it! You can embed images, format text, and make folders.

Check out [CommonMark](https://commonmark.org/help/) for a quick guide, or [Obsidian Markdown](https://help.obsidian.md/syntax), for the specific flavor we support for advanced things like call outs and diagrams.

As soon as the new files are added (when your *pull request* is approved by a few people who make sure the site still loads, etc.) The site will automatically show your new page, or updates!

### How to use git for contributing film notes

- Read up about [Forks](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo)
- In doubt, ask someone listed in the repo or FilmExperiments organization!

### (For development-interested folks)

#### Restore

prerequisites:

- Node JS V22

- Run `npm install` in the base folder of the repo.  

#### Compile/Serve

- Build locally: `npx quartz build`
- Run locally: `npx quartz build --serve`
