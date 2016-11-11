glossary.png?label=in%20progress&title=In%20progress)

# iSAQB Software Architecture References

A curated (and somewhat commented) list of software architecture references,
many of them used in the iSAQB foundation and advanced level curricula.

![](./images/glossary-cover-small.jpg)

This repository contains the sources for the published version of
the iSAQB references, available both online and in various eBook formats
at [Leanpub (https://leanpub.com/isaqbreferences)](https://leanpub.com/isaqbreferences).

This book is made possible by **collaborative effort** of several
[iSAQB e.V.](http://isaqb.org) members.
It's intended to **support the non-profit interests** of
the iSAQB and the software architecture community in general.


## Suggestions Welcome

We welcome suggestions and critique of any kind: Just
[open an issue](https://github.com/isaqb-org/glossary/issues)
here on Github!

## Book Generation (aka "build")

This repository is linked with Leanpub over a webhook: Every commit in `master` triggers
a preview-build at Leanpub. The results (in pdf, mobi and epub formats) are stored in
a Dropbox folder. Authors and contributors are given access to this Dropbox.


## About personal opinion

As this collection combines the efforts of several authors, some _personal opinions_ or
comments might be added, to give a broader perspective on some of the references.

If you want to add your opinion or comment to any term in the glossary, please
use the "discussion sidebar" syntax like shown below:

```
D> ###### Comment (Gernot Starke)
D> In my personal opinion, it does not work in practical situations, only in hello-world-like scenarios, as the inverse abstraction (from low-level sourcecode to higher-level architectural elements) usually involves design-decisions and cannot realistically be automated.
D>
D> ###### Comment (Matthias Bohlen)
D>Recently I have seen code that originated from DDD where reverse engineering did indeed work.
```

This will yield the following output (captured from the pdf version, will look different in web or epub versions):

![](./images/comment-sample.jpg)


## Contributors


This content is maintained by volunteers from the [iSAQB e.V.](http://isaqb.org),
a non-profit volunteer association - see the contributors list of this repository.



Statements of the form "xy should be done, but I won't do it.." without further
contributions do not qualify as _significant_.  

#### How to Become an Author

You can become contributor/author (and will be added to the Leanpub contributor page) if
you: 

1. Fix an issues from the Github issue list
2. Add a new reference that is accepted at least two of the existing authors.
3. Provide significant other input by mail or other means to existing authors.

(You need a (free) Leanpub account to become an author.)

## Donating to EEF (Electronic Frontier Foundation)

All royalties from Leanpub sales of this book are donated to
the [Electronic Frontier Foundation (eff.org)](http://eff.org).

![](./images/eff-logo-name-72.jpg)



## License

This book is licensed under a
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).


![](./images/cc-by.png)

The following is only a brief summary and no substitution for the real
[licence](https://creativecommons.org/licenses/by/4.0/).


The cc-4.0-by license means that you might:

* Share — copy and redistribute the material in any medium or format
* Adapt — remix, transform, and build upon the material for any purpose, even commercially.
* The licensor cannot revoke these freedoms as long as you follow the license terms.

You must:

* Give **appropriate credit**,
* Provide a link to the license (https://creativecommons.org/licenses/by/4.0/), and
* Indicate if changes were made.
