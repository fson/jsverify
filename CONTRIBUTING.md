## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style.

- Add unit tests for any new or changed functionality.
- Lint and test your code using `make test`.
- Use `make istanbul` to run tests with coverage with [istanbul](http://gotwarlost.github.io/istanbul/).
- Create a pull request

### Before release

Don't add `README.md` or `jsverify.standalone.js` into pull requests.
They will be regenerated before each release.

- run `make dist`
