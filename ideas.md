# Potential titles for the talk

- Things I wish I knew about Python sooner
- Things I wish I knew sooner
- Be lazy. Tips for easier code
- Tricks for python data manipulation
- Ten tips for data manipulation
- Security data manipulation and enrichment
- The 10 secrets professional Python programmers dont want you to know
- These 10 weird tricks make your python go from good to great!

# Things we might talk about

- collections.Counter
- dict.get
- IPython or beaker notebook
- Probably some data frame tricks
- dealing with Unicode <- ermahgerd!!!
- argparse replacing optparse
- requests instead of urllib2
  - grequests for multiple parallel requests
- `substr` in `string` instead of regexes (when `substr` is just characters)
- list comprehensions
- with open(filename, 'rb') as f: (contexts)
- generators
- prettyplotlib

"you must unlearn what you have learned"


# Integrating examples
We were talking about spending a short amount of time on several of the ideas
and then using an integrating example to bring them all together. So we might
spend 1 each talking about dict.get, collections.counter and with open(filename).
Then we would have an example where we want to open every file in VCDB, load the json,
get hacking variety (if present) and count the most frequent examples.

We could spend 1 minute each talking about argparse and requests and parallel requests.
Then have an example where you write a script that allows a person to read a file or
take input from stdin that is a list of ip addresses. Then use requests to pull
geolocation data for each of them and maybe write the output to a file. If there are
a lot of ip addresses make parallel requests to speed up the process.

Alternate examples between presenter. One shows "old and busted" first, then other explains "new hotness". For next example, switch.
