# momus end-to-end test

A private test repository for [momus](https://github.com/brianluby/momus-review).
`main` holds only the momus workflow; a pull request adds all of
[OWASP Juice Shop](https://github.com/juice-shop/juice-shop) at commit
`1618a611b` (MIT licensed, a deliberately vulnerable app) so the action
reviews a large, known-vulnerable diff. Juice Shop's own `.github/`
directory is left out so its CI does not run here.
