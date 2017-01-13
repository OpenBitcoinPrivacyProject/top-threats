## Technical

Please provide feedback on any of the following:
* Choice of categories
* Should we add additional threat categories? Please start with the categories
 indicated in
 [this spreadsheet](https://docs.google.com/spreadsheets/d/1qan5rsSB7UTboIfrOlPtKBy0GDkml29_JKyxlNUyH4Y/edit?usp=sharing)
 first, or argue why those categories should be changed. See FAQ below.
* Review the content of each threat category.
* If you write Bitcoin software libraries or have used them, please consider
 submitting code examples of how to mitigate specific threats using the library
 of your choice.
* If you've read academic papers or whitepapers on privacy, please let us know
 which threat category they are relevant to as references. Here's a
 [list of whitepapers](https://docs.google.com/spreadsheets/d/1washrMyOa1pWDFPmux-Va9dgxA-Vz-0HO5fvMPsRUWU/edit?usp=sharing)
 we've partially reviewed from the Bitcoin Wiki. If there are relevant websites,
 please submit these as references, as well.

## Non-technical

Non-technical reviewers can help out by copy editing (correcting mistakes and
 clarifying language) and by giving feedback on how comprehensible the text is.
 In general, most of the content should be understandable to laypeople, and for
 the portions that are specific to technical audiences, it should be clear when
 this is the case (e.g. discussing examples in programming code).

## FAQ

1.  Why start with just 3 categories?

    This project is modeled after the OWASP Top 10 project. After organizing the
    criteria in our 2nd edition threat model, we determined that there weren't
    10 well-defined threat categories presently, which is what you'd expect for
    a field that is much newer than Web application security. These first 3
    threat categories account for 68% of the weight assigned to the criteria in
    our 2nd edition threat model. Over the years, we expect that the number of
    threat categories covered by this project will increase. Note that our
    threat model is the primary project intended to cover many threats, while
    this project should focus on the ones that are **most important** for
    everyone to know about.

2.  Where can I find the second edition threat model?

    This is currently split into two documents. The
    [“threat model” document](https://github.com/OpenBitcoinPrivacyProject/wallet-ratings/blob/master/report-02/threat%20model.wiki)
    lists the attacker, attack, and countermeasure categories . The
    [“criteria” document](https://github.com/OpenBitcoinPrivacyProject/wallet-ratings/blob/master/report-02/criteria.md)
    lists the criteria under the various countermeasure categories . The third
    edition of the threat model imposes a JSON-based format for all of this data
    as well as generated documentation; we will back-port the second edition to
    this new format once the format has been finalized.

3.  What kind of feedback should I provide?

    Our goal is to make sure that the threat categories meet these criteria:
    * They should be common and severe, more so than other categories
    * The categories should be well-defined and make sense
    * The categories should be relevant to both users and developers

    The copy for each attack category should be include a succinct and
    jargon-free explanation for common users.

    Ultimately, we would love to be able to offer specific technical feedback to
    developers on how to identify and fix these vulnerabilities. Ideally we
    could provide example code in a variety of languages and/or for a variety of
    popular Bitcoin software libraries. If you have any expertise in this area,
    consider contributing.

    Editorial feedback on the copy is also welcome.

4.  How flexible will these documents be in the future?

    After the "public comment" period has passed, the threat categories and
    their identifiers will enter a *change freeze*. However, the rest of the
    copy may be updated as necessarily. Most likely, changes to the current
    edition will peter out as we start working on on the next version.

5.  How long do I have to provide feedback?

    Please see the calendar listed under the [README](README.md).

## Contact

You can provide feedback in the form of
 [GitHub issues on this repository](https://github.com/OpenBitcoinPrivacyProject/top-threats/issues)
 and comments on
 [open pull requests](https://github.com/OpenBitcoinPrivacyProject/top-threats/pulls).

You may also heckle us on Twitter [@obpp_org](https://www.twitter.com/obpp_org)

The best way to ensure that your feedback is incorporated is to submit a pull
 request. Refer to: [HOW-TO-CONTRIBUTE.md](HOW-TO-CONTRIBUTE.md).
