<h1 align="center">
<img src="https://raw.githubusercontent.com/atlacoin/atlacoin-com/refs/heads/master/img/logo.png" alt="Atlacoin" width="256"/>
<br/><br/>
Atlacoin [ATLA]
</h1>

**Atlacoin (ATLA):** *In a world divided by four elements — Memes, Stonks, FOMO and Diamond Hands — only one coin can bring balance to your crypto portfolio. Powered by the Scrypt PoS (Proof of Stake) algorithm, Atlacoin bends profits like Aang bends air. Just remember: with great power comes great volatility… and occasional moonshots.*

**Become an Avatarian to get free Atlacoins for staking and let your portfolio achieve inner balance.**

| [X (Twitter)](https://x.com/atlacoin) | [Discord](https://discord.gg/3hWQduVRtD) | [Reddit](https://www.reddit.com/r/atlacoin) |

What is Atlacoin Core?
----------------

Atlacoin Core is the name of open source software which enables the use of this currency. It takes Atlacoin to the next level by building upon
Bitcoin Core 0.13.2 with some patches from newer Bitcoin Core versions to offer performance enhancements, wider compatibility with third party services and a more advanced base.

For more information, as well as an immediately useable, binary version of the Atlacoin software, see https://atlacoin.com.

License
-------

Atlacoin is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/atlacoin/atlacoin/tags) are created
regularly to indicate new official, stable release versions of Atlacoin.

Change log can be found in [CHANGELOG.md](CHANGELOG.md).

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md).


Testing
-------

Testing and code review might be the bottleneck for development. Please help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](/doc/unit-tests.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`

There are also [regression and integration tests](/qa) of the RPC interface, written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/qa) are installed) with: `qa/pull-tester/rpc-tests.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and OS X, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.
