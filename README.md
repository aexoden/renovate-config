# renovate-config

This is a highly-opinionated set of [Renovate](https://www.mend.io/renovate/)
configuration files used by my own projects. I highly recommend forking this
repository rather than using it directly, as the configuration may change at any
time without warning. If you insist on using it directly, you can do so as follows:

```json
{
    "extends": ["github>aexoden/renovate-config"]
}
```

Alternately, you can specify a specific preset:

```json
{
    "extends": ["github>aexoden/renovate-config//automerge"]
}
```

## License

To the extent that any of this is non-trivial enough to be copyrightable, it is
licensed under the MIT license ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>).
