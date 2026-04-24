## Morning Planning

<img alt="Octocat" src="https://camo.githubusercontent.com/41b11d9d905f1d49231e9b6d120fdca8db39a5a865ece4850014a0ae75172a14/68747470733a2f2f6f63746f6465782e6769746875622e636f6d2f696d616765732f6f726967696e616c2e706e67" width="100" align="right">

- [ ] Check out the [github blog](https://github.blog/) for topic ideas.
- [ ] Learn about [GitHub Pages](https://skills.github.com/#first-day-on-github).
- [ ] Convert my first blog post into an actual webpage.

## Review

Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
