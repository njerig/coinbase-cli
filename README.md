# btc

Buy, sell, and transfer [bitcoin](http://bitcoin.org/en/) instantly at your
terminal!  (Powered by [Coinbase](https://coinbase.com/).)


## Prerequisites


## Installation

You can install `btc` via [pip](http://pip.readthedocs.org/en/latest/):

```bash
$ sudo pip install btc
```

Once `btc` has been installed, you'll need to give it your coinbase API key so
it knows how to make requests.  You can find your coinbase API key here:
https://coinbase.com/account/integrations (make sure your API key is
*enabled*).

```bash
$ btc start
```

The `start` command will ask you for input, and walk you through the making sure
that `btc` is working properly.  Your API key will be stored in a file named
`~/.btc` in your home directory.  To remove your API key from `btc`, simply
delete that file.


## Usage

If you simply run `btc` on the command line, you'll get a list of help.

```bash
$ btc start     # activate btc by supplying your coinbase API key
$ btc logs      # list your coinbase transactions
$ btc view      # list current buy / sell rates
$ btc buy 1     # purchase 1 bitcoin using your bank account on file
$ btc sell 1    # sell 1 bitcoin
$ btc transfer 1 <someaddress>
                # transfer 1 bitcoin to the specified address
```

All of the commands above (except the `logs` and `view` commands) require you
to manually accept (by pressing `y` or `n` on your keyboard), for added
security (so you don't accidentally spend tons of money, or something).


## Like This?

If you've enjoyed using `btc`, feel free to send me some bitcoin!  My address
is:

**14m3gaa3TvEgN7Ltc4377v3MVCPnyunuqS**

<3

-Randall
