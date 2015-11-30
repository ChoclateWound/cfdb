# Common Findings Database

Source: https://github.com/mubix/cfdb

The Common Findings Datase is a collection of markdown based findings writeups.
The goal of which is 3 fold:

1. Create a place for collaboration to happen in regard to findings
2. Help to unify finding recommendations and references
3. Assist new and upcoming Information Security professionals in learning

You can find the live, searchable version at http://cfdb.io/

If you wish to contribute, you can do so in a couple ways:

1. If you hate git, and everyone can understand that, simply copy and paste text into an "Issue" and we'll format it correctly and give proper attribution
2. If you are so bold, please submit pull requests

Our format will be as follows so you can easily copy and paste it to get you started (you do not have to include an sections that are not applicable, or that you simply don't want to write):

```
/*
Title: Finding Title
Description: Search engine meta data about the finding
*/

- LAST UPDATED DATE: 
- LAST UPDATED BY: 

## Summary

A brief summary of the finding

## Capabilities and Risk

This is to replace any "level" or "score" because of how much context is needed
for a finding to have one, which is beyond the scope of this database.

- List of possible uses for this finding to give real-world uses
- Read files as www-data (or use web server is running as)
- DDoS service
- Code execution (for this one to fly there needs to be a refence proving it)

## Detection

How does one detect the exploitation of this finding, or detect its presence.

## Remediation

What are some of the ways to fix this finding?

## References

- Link to blog post
- Link to CVE
- Link to Metasploit module
- Link to Nessus/NeXpose/Qualys write up

## Exploitation

A write up on how this finding can be exploited with demo code or screen shots


```
