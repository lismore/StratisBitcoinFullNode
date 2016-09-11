# StratisBitcoinFullNode
=====================================
https://stratisplatform.com

What is Stratis?
----------------

Stratis is an experimental new digital currency that enables instant payments to
anyone, anywhere in the world. Stratis uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Stratis Core is the name of open source
software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Stratis Core software, see https://stratisplatform.com/download, or read the
[original whitepaper](http://stratisplatform.com/files/Stratis_Whitepaper.pdf).

License
-------

StratisBitcoinFullNode is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).

The developer [mailing list](https://lists.linuxfoundation.org/mailman/listinfo/stratis-dev)
should be used to discuss complicated or controversial changes before working
on a patch set.

Developer IRC can be found on Freenode at #stratis-core-dev.

Testing
-------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](/doc/unit-tests.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.

Translations
------------

Changes to translations as well as new translations can be submitted to
[Stratis Core's Transifex page](https://www.transifex.com/projects/p/stratis/).

Translations are periodically pulled from Transifex and merged into the git repository. See the
[translation process](doc/translation_process.md) for details on how this works.

**Important**: We do not accept translation changes as GitHub pull requests because the next
pull from Transifex would automatically overwrite them again.

Translators should also subscribe to the [mailing list](https://groups.google.com/forum/#!forum/stratis-translators).
