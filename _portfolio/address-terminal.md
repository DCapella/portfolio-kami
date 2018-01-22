---
layout: post
title: Address Terminal
thumbnail-path: "portfolio/address-terminal.png"
short-description: A virtual address book coded with Python 3 with self tests.

---

{:.center}
![]({{ site.baseurl }}/portfolio/address-terminal.png)

## Explanation

Address Terminal is an application that can be used to store names with a phone number and email. You will be able to view, create, search and even import entries from a CSV. (As you can see in the picture)

## Problem

Users need to be able to:

* Store entries
* Edit entries
* Delete entries
* View entries
* Search entries
* Import entries

## Solution

Using Python 3 to build Address Terminal allows users to easily store and retrieve entries. It also allows me to test the features in one file.

{% highlight python %}
# start of tests
print("="*25 + "\nSTART OF TESTS" + "\n" + "="*25)
errors = 0

book = AddressBook()

print("Entries = 0")
if len(book.entries) == 0:
    print("SUCCESS")
else:
    print("FAIL")
    errors += 1
{% endhighlight %}

## Results

Fun project that allows users to view, create, search and import entries from a CSV.

## Conclusion

In conclusion, it was a good project to help me practice different aspects of Python 3, as well as create my own test cases.
