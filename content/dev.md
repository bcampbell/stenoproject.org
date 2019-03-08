## Development

### Source code

Most of the Steno tools are written in [go](https://golang.org).

The source for the Front end tools (Steno, steno-similar) can be found at: https://github.com/bcampbell/steno

The back end tools (scrapeomat, slurpserver etc) are at: https://github.com/bcampbell/scrapeomat


### Status

The Steno GUI tool is in quite a bit of flux at the moment.

It originally used the [go-qml](https://github.com/go-qml/qml) bindings to provide a Qt/QML GUI. However, go-qml hasn't really been maintained recently, and packaging up builds with the Qt libraries always got a little awkward.

The current plan is to switch over to a [libui](https://github.com/andlabs/libui)-based GUI.
There is a `ui` branch of steno with a rough proof-of-concept version already working. It's still missing a bunch of features, but is simple, fast and easy to package. it looks promising.


### License

The Steno tools are released under the [Affero GPL (v3)](https://www.gnu.org/licenses/agpl-3.0.en.html).


