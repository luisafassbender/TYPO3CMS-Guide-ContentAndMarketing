.. include:: /Includes.rst.txt

.. _writing-style-guide:

===================
Writing Style Guide
===================

**By using this style guide we ensure that all written texts have the same general grammar and writing style — even when many people contribute. This guide should be easy to use, and it is based on the existing proto house style used at typo3.org.**

Style guides can become very, very long. We keep this guide short to make sure you read it, but it means we only cover the most important topics. If you would like to read more about style and usage, check out `Jack Lynch’s Guide to Grammar and Style <http://jacklynch.net/Writing/>`__, read the `Google Developer Documentation Style Guide <https://developers.google.com/style/>`__, or buy the `Chicago Manual of Style <http://www.chicagomanualofstyle.org/>`__ (after all, it is abbreviated CMS).

.. _spelling:

Spelling
========

We write using American (US) spelling. That means we write color, rather than *colour, and use -ize endings, rather than *-ise.

.. _dictionary:

Dictionary
==========

If the spelling of a word is disputed, `Merriam-Webster’s Dictionary <https://www.merriam-webster.com/>`__ has the correct answer.

.. _title-case:

Title Case
==========

We capitalize all principal words of a title, including the first and the last words. We do not capitalize articles, prepositions or conjunctions that have fewer than four letters, such as:

* a
* an
* and
* at
* but
* by
* for
* in
* nor
* of
* on
* or
* so
* the
* to
* up
* yet

To avoid thinking, use the *AP* captialization at `capitalizemytitle.com <https://capitalizemytitle.com/>`__, and beware that we are using a somewhat simplified rule.

.. _title-case-examples:

Examples:
---------

TYPO3 Is Great

How to Configure Your Development Environment

.. _buttons:

Buttons
=======

Buttons are capitalized using Title Case.

.. _numbers:

Numbers
=======

Numbers are written using a dot “.” as decimal separator and comma “,” as thousands separator. We normally use max two decimals. The number of decimals used should reflect the text's need for accuracy.

The thousands separator can optionally be omitted for numbers 1,000–9,999.

A zero should be included before the dot in numbers less than 1.0.

Very large integer numbers (those above 999,999) should be written using million, billion, or trillion, replacing the last six or nine digits.

Numbers less than ten are spelt out, unless they are dates or part of a list with larger values.

.. _numbers-examples:

Examples:
---------

The Association has 12,481 members.

The function nesting limit is set to 1000.

That is exactly 99.96% true.

The file has more than 30 million lines.

All of the three million TYPO3 users are geniuses.

I need at least five developers.

Choose between the numbers 4, 42, and 64.

The difference is less than 0.5.

.. _currency:

Currency
========

Currency values are written using the three-letter ISO code, followed by a space, followed by the value written according to our number style.

Currency symbols, such as € and $ can be used as a shortened form. They are placed in front of the value, with no space separating them.

.. _currency-examples:

Examples:
---------

The tickets cost EUR 1,000.

We made a profit of exactly USD 25,060.17.

Grab it now, for just €1.

.. _dates:

Dates
=====

We prefer the international date style: day, month, and year. We always write the month name. Dates written as numbers only will cause confusion for our international audience. Years are always written in four digits.

Month names are normally written in full, but can be abbreviated if you lack space, as rendered by the PHP function date('M.'): Jan., Feb., Mar., Apr., May., Jun., Jul., Aug., Sep., Oct., Nov., and Dec.

.. _dates-examples:

Examples:
---------

24 December 2018

12 Sep. 2009

.. _comma-in-lists:

Comma in Lists
==============

We use the so-called Oxford (or serial) comma, setting a comma before the final “and” or “or” in a list with three or more items.

.. _comma-in-lists-examples:

Examples:
---------

Apples, orange, grapes, and bananas.

I eat Chinese gooseberries and pineapples.

Would you like potatoes, carrots, or leeks?

.. _dashes:

Dashes
======

We use an em-dashes without spaces around to mark parenthesis. We use n-dashes without spaces around to mark from–to in a number series.

.. _dashes-examples:

Examples:
---------

TYPO3—not any other CMS—is my favorite.

There are 20–25 options available.

.. _quotes:

Quotes
======

Exact quotes are written between double quotation marks. Quotes within quotes are written between single quotes. For long quoted sections, we use indented block quotations without quotation marks. Periods and commas are placed within quotation marks. Colons and semicolons are placed outside of quotation marks.

Changes and omissions within quotes are [in brackets].

.. _quotes-examples:

Examples:
---------

I felt great each time he said “I love TYPO3.”

“I love TYPO3,” he said enthusiastically.

He said he “ha[d] no idea why people said ‘hello’ all the […] time.”

The poem goes:

    Roses are red
    Violets are blue

.. _emphasis:

Emphasis
========

We use *italics* for emphasis on single words or compound words. **Bold** text is used to increase visibility on words, compound words, parts of sentences, and sentences. We never use underlined text.

.. _emphasis-examples:

Examples:
---------

Becoming a member is *very* important.

This year’s **accounts are looking very good**.

This text is *not* underlined for emphasis.
