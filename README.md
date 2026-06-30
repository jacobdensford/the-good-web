![](/images/icon128.png)

# The Good Web

*Welcome to the good web.*

The Good Web is an introduction to the independent web, a guide to becoming part of it, and a feed reader with a collection of feeds to get started. 

## Details

### Introduction and Guide

The homepage introduces the independent web and walks newcomers though discovering website, curating their own collection of feeds (and selecting a feed reader), participating in online communities, and creating a website of their own.

### Feed Reader and Feeds

The Good Web also includes a static feed reader that aggregates a curated collection of RSS and Atom feeds into daily and weekly editions. The default feed collection encompasses topics of interest to a wide audience, as well as my own preferences, but it can be replaced with a user's own OPML file (see [Development](#development) below).

## Usage

![Screenshot showing The Good Web homepage](example-1.png)

Visit [web.cobb.land](https://web.cobb.land) to use The Good Web.

- Read the homepage for an introduction to the independent web.
- Browse the daily or weekly editions to discover new websites and read posts.
- Clone the project and replace the included OPML file with your own collection to build a personalized feed reader.

## Development

- Clone repo
- Run `npm install`
- Optionally replace `data/feeds.opml` with your own collection of feeds
- Optionally set `weeklyEditionDay` in `scripts/goToPrint.js`
- Run `npm run fetch` to get feeds
- Deploy to static web host
- To update, run `npm run fetch`, then push to host

## Roadmap

- [ ] Further articulate opinions on "opinionated" page
- [ ] Make better default OPML for introduction to the good web
- [ ] Add keyboard navigation

## Contribute

If you would like to contribute to this project, please fork and make a pull request. Also, if you have suggestions or find bugs, please feel free to open an issue.

## License

[GNU GENERAL PUBLIC LICENSE](LICENSE)

## Contact

[hello@jacobdensford.com](mailto:hello@jacobdensford.com)

