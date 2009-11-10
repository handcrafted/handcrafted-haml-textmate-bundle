#Handcrafted HAML TextMate Bundle

##Description

Forked from the Handcrafted HAML TextMate Bundle.  Additions include

 * <code>{}</code> not in <code>=""</code> is still recognized by the language as embedded ruby source
 * Added snippet/command <code>ctrl + ></code> (same as the erb keystroke to add <code><%= %></code> and toggle between erb styles) which will insert <code>#{}</code> and toggle between <code>#{ruby code}</code> and <code>#{ ruby code }</code>
 * Added html language (lowest priority). Helpful when your haml includes things like &amp;amp;. Also helpful if you're mixing haml with html.
 * Added more helpful snippets for ruby style attributes (: and => triggers)
 * Updated language so that < and > are recognized as HAML constants (language is still smart enough such that when < and > are used with HTML or erb, it treats it as such)

##Credits

Additions by [Philippe Huibonhoa](http://github.com/phuibonhoa)

Original Bundle Created by [Adam Stacoviak](http://www.adamstacoviak.com/ "Adam Stacoviak | Web Development, Interface Design, User Experience &amp; Internet Marketing"), co-founder of [Handcrafted](http://gethandcrafted.com/ "Handcrafted &ndash; Ruby on Rails Development Consulting Firm, Interface Design, User Experience, Web Marketing"), a Rails Development Consulting Firm.

Parts of this bundle were ported from the official Ruby Haml TextMate bundle. The filter snippets were ported from [Matt Polito's ruby-haml.tmbundle](http://github.com/mattpolito/ruby-haml.tmbundle/tree "mattpolito's ruby-haml.tmbundle at master - GitHub").

##Installation

1. $ `cd ~/Library/Application\ Support/TextMate/Bundles/`
2. $ `git clone git://github.com/handcrafted/handcrafted-haml-textmate-bundle.git HAML-Handcrafted.tmbundle`
3. $ `osascript -e 'tell app "TextMate" to reload bundles'`