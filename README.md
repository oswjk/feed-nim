# Feed-Nim
A feed parsing module for Nim, which reads RSS, Atom, and JSONfeed syndication formats. This was a re-written and expanded from [Nim-RSS](https://github.com/achesak/nim-rss)

## Usage

<code>loadAtom(filename: string): Atom</code> Loads the Atom from the given _filename_

<code>getAtom(url: string): Atom</code> Gets the Atom from the specified _url_

<code>loadRSS(filename: string): RSS</code> Loads the RSS from the given _filename_

<code>getRSS(url: string): RSS</code> Gets the RSS from the specified _url_

<code>loadJsonFeed(filename: string): JSONfeed</code> Loads the JSONFeed from the given _filename_

<code>getJsonFeed(url: string): JSONfeed </pre>JsonFeed = JSONFeed from the specified _url_
