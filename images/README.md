# Screenshot sources

These are current Chromium screenshots using `ie-scrollbar.js`, not original screenshots from Internet Explorer.

| Image | Page | Saved date |
| --- | --- | --- |
| [dance.archi](dance-archi.png) | [Yello](https://dance.archi/pages/yello.html) | Current page |
| [Tams](myspace-tams.png) | [MySpace archive](https://web.archive.org/web/20060411202310/http://profile.myspace.com/index.cfm?fuseaction=user.viewProfile&friendID=2232347) | April 11, 2006 |
| [Lily Allen](myspace-lily.png) | [MySpace archive](https://web.archive.org/web/20060411135334/http://myspace.com/lilymusic) | April 11, 2006 |
| [Happy Rainbow Mushies](myspace-rainbow.png) | [Original layout](https://www.createblog.com/myspace-layouts/18351-happy-rainbow-mushies/) · [Archived preview](https://web.archive.org/web/20090425014754/http://www.createblog.com/myspace-layouts/18351-happy-rainbow-mushies/preview/) | Layout June 2007; archive April 25, 2009 |

The MySpace HTML and recovered images/stylesheets come from the Internet Archive. The pages retain their authored scrollbar palettes. In screenshot copies, hashless hex colours received a `#` and `!important` suffixes were removed from legacy scrollbar declarations. Unrecovered image assets were omitted; old scripts and embedded players were omitted. Lily Allen’s empty `.r{}` IE hacks and a line break inside a property name were removed so the authored palette parses correctly. Tams's original `lilac` track value is not a valid CSS colour and is left unchanged.

The Rainbow screenshot comes from [the restored live layout](https://dance.archi/scrollbars/myspace/rainbow.html), using falsetigerlimbs’s original artwork and CSS. Hex colours were normalized, an outer positioning container preserves the overlay when scrollbars mount, and the unavailable comment-button image has a plain button replacement. MySpace actions are inactive. [Artwork sources](../examples/myspace/assets/README.md).

The dance.archi screenshot uses its page and assets with this repository's script in place of its existing scrollbar scripts.

The CSS reference images are rendered from [the live examples](https://dance.archi/scrollbars/options.html). The star and checkerboard assets are included in [examples/assets](../examples/assets/). Most examples use DPR 1.5; the fixed-dither example uses DPR 2.5.

Third-party page artwork belongs to its original owners; the project's MIT license applies to its code and original examples.
