# momus example: reviewing OWASP Juice Shop

A public example of the [momus](https://github.com/brianluby/momus-review)
GitHub Action on a large, known-vulnerable diff. `main` holds only the momus
workflow; [pull request #1](https://github.com/brianluby/momus-juice-shop-test/pull/1)
adds all of [OWASP Juice Shop](https://github.com/juice-shop/juice-shop) at
commit `1618a611b` (MIT licensed, a deliberately vulnerable app), and momus
reviews it: inline comments on the diff plus one summary comment.

Juice Shop's own `.github/` directory is left out so its CI does not run
here. Do not merge the pull request; it exists to show the review.
