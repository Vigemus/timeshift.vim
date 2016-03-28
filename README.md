Split Join
==========

This simple plugin splits into another buffer and then joins back into
original place.

To split something, simply do `csj{motion}` and the piece of text relative
to the supplied motion is splitted into another buffer.

After you are done editing in this separate buffer, simply do `q` and the
text is joined back into where it was before.

If you are inside a markdown buffer, you can `cmd` (_c_hange _m_ark_d_own) inside a code block (triple
backticks) that it will automatically open a scratchpad buffer with the code
block content with the correct filetype set.

Please note that this plugin makes heavy use of marks, specially the mark `'s`.
If you use marks frequenty, avoid marking `'s` on the same file that you are
running splitjoin.
