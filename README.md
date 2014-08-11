# code-of-conduct-diffinator

_An archive of programming conferences' code of conduct policies. In tasty plain text, with metadata, so they can be diffinated painlessly._

===

## Why
Ability to explore programming conference codes of conduct -- how they derive, adapt, and inspire others -- gives us valuable insights; as programming conference organizers who seek create a code and refine it, as community members who are held accountable for upholding it, and as sponsors who evaluate whether to support it.

Exploring a spectrum of approaches, and their nuances of language, gives us insights into conferences' values, vision, and expectations.


## Usage

$ git clone https://github.com/cczona/code-of-conduct-diffinator.git

$ cd code-of-conduct-diffinator

$ diff -y `conference-1.md` `conference-2.md`

### Alternate Usage

There are many alternatives to the `diff` command. For comparing codes of conduct, word or character diffs are more informative anyway.

#### opendiff

Xcode Commandline Tools includes a nice GUI called FileMerge.app, which does word diffs. Invoke it at the commandline as`$ opendiff`.

#### colordiff

`$ colordiff -y -d` 

#### gvim

`$ gvim -d`
    

## Crediting

When developing a code of conduct for your programming conference, please attempt to credit the sources it draws upon, so others can likewise benefit from understanding differing approaches. For example:

    Adapted from the codes of conduct by JsConfEU <http://2013.eurucamp.org/policies> and Geek Feminism <http://geekfeminism.wikia.com/wiki/Conference_anti-harassment/Policy>, using source materials archived at <https://github.com/cczona/code-of-conduct-diffinator>


## Contribute!

   Does your conference publish a code of conduct? **We <3 pull requests.** See `CONTRIBUTING.md` for info.


===


`code-of-conduct-diffinator` is maintained by @cczona for [CallbackWomen](http://callbackwomen.com) \<http://callbackwomen.com\>
