# Introduction

An emacs command that is clone of "ci" in vim.  
You can use ci", ci', ci(, ci{, ciw, cit. 

![circleanimationmuvie](https://raw.githubusercontent.com/cs14095/cs14095.github.io/master/ci-el.gif) 

# Installation

Download ci.el somewhere.  
For example:


	cd ~/.emacs.d/elisp/
	git clone https://github.com/cs14095/ci.el


Then add the following in your .emacs file:


	(setq load-path (cons "~/.emacs.d/elisp/ci.el" load-path))
	(require 'ci)


# Usage

Press `Ctrl-c, i` and enter available character.  
Watch example or vim usage.  


# Example

	Ctrl-c, i, w => kill a word  
	Ctrl-c, i, t => kill inside of <>  
	Ctrl-c, i, ' => kill inside of ''
	Ctrl-c, i, " => kill inside of ""  
	Ctrl-c, i, ( => kill inside of ()  
	Ctrl-c, i, { => kill inside of {}

you can also kill nested parentheses as you can see.

![circleanimationmuvie](https://raw.githubusercontent.com/cs14095/cs14095.github.io/master/ci-el.gif) 

# Conclusion

Almost commands that I know are ready, but some commands are not beacuse of my coding issues and difficult of emacs lisp.  
I will continue to add commands and fix bugs, so please give me any comments.
