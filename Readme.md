# byways

Content of the closed `byways.org` website hosted at [scenicbyways.info]. It contains descriptions,
maps and links to related information for over 800 America's most scenic roads.

It displays maps from [Furkot] and photos from [Panoramio].
Comments are provided by [Disqus], and custom search engine -- by [Google].

Site is generated by [Wintersmith]

## Building

To preview the website:

    npm install
    make components preview

To build a static version:

    make build


## Contributing

Fork and have fun. We take patches and update hosted version regularly.
If you modify .js files make sure you `make lint` it.

If you work for any of the organizations that used to contribute to `byways.org` and want to update
information on your byway but don't feel like dealing with this `git` thing, drop us an e-mail at
[byways@code42day.com]

## License

We believe the content of the website (.json files in the `contents` directory) is in public domain.
It was available from `bywaysonline.org` run by [FHWA] before that site and the byways program was
defunded. If you think otherwise please contact us at [byways@code42day.com]

Everything outside of the `contents` directory (styles, javascript, jade templates etc.) is
published under MIT license.

### Icon Fonts

Icon font generated by [Iconmoon] application:

* [IcoMoon - Free](http://keyamoon.com/icomoon) [CC BY 3.0](http://creativecommons.org/licenses/by/3.0)
* [Icon Minia](http://dribbble.com/shots/598215-Icon-Minia-139-Vector-Icons) [GPL V3](http://www.gnu.org/copyleft/gpl.html)

[Car][car.icon] designed by [Diogo Trindade][car.author] from The Noun Project

[scenicbyways.info]: http://scenicbyways.info
[FHWA]: http://www.fhwa.dot.gov (Federal Highway Administration)
[byways@code42day.com]: mailto://byways@code42day.com
[Furkot]: https://trips.furkot.com (Road trip planner)
[Panoramio]: http://www.panoramio.com
[Disqus]: http://disqus.com
[Google]: http://google.com/cse
[Wintersmith]: http://wintersmith.io
[Iconmoon]: http://icomoon.io
[car.icon]: http://thenounproject.com/noun/car/#icon-No23068
[car.author]: http://thenounproject.com/diogo.soares.trindade