---
title: "First Impression"
date: 2019-03-24T18:22:47-03:00
tags: [software-arch,programming]
draft: false
---
As a software achitect, sometimes, people is more challenging than software. Bad practices propagate at speed of light because, like it or not, programmers tend to copy-paste more than you think (and more than they like to admit).

So, you find yourself building a really small microservice reusing code from another project (yes, copy-pasting), and there it is; the boogie man code waiting for you in the dark corner of some critical and productive code.

{{< highlight python >}}
	def some_fancy_function():
		try:
			r = some_genius_code()
		except Exception as e:
			return e
		return r
{{< /highlight >}}

At first glance you don't understand, of course, you've read wrong so you pay attention and your heart rate accelerates, your brain starts to make connections and your coding voice sits on your left saying: "It's code in production."

Panic! Your reptilian brain thinks in slaughtering an entire dev team.

But, this is 2019, we're professionals (yes, professionals wrote that code), so you end up explaining to ~40 devs, plus tech leads, how exceptions work, and how they should be properly used.

## Conclussion

At the "exceptions talk", some dev faces were priceless! :-)

