#HAML TextMate Bundle

##Description

Forked from the Handcrafted HAML TextMate Bundle.  Additions include

####Improved Language
 * Text inside ERB and Javascript filters are now properly recognized so you get all the syntax highlighting, snippets, commands, etc.
 * Added built-in html recognition. Helpful when you include html in your haml.
 * Ruby code inside <code>#{}</code> recognized as embedded ruby
 * Updated language so that < and > are recognized as HAML constants

####Added snippets and commands
 * <code>⌘⌥+C</code> converts selection from HTML to HAML (and tries to convert erb to haml style - still beta-y)
 * <code>⌃+></code> inserts <code>#{}</code> and toggles between <code>#{ruby code}</code> and <code>#{ ruby code }</code>
 * Added snippets for attributes (<code>:⇥</code> and <code>=></code>)
 * Added full trigger snippets for common html elements (ie table, br, div, h1, h2, etc.)
 * <code> ⌘+/</code> uses rails comments -# instead of HTML comments
 * <code>⌘⌥+X</code> escapes HTML special characters
 
####Other Textmate Bundles
My bundles work best when use in conjunction with my other bundles:
 * Rails - http://github.com/phuibonhoa/ruby-on-rails-tmbundle
 * Ruby - http://github.com/phuibonhoa/ruby-tmbundle
 * Shoulda - http://github.com/phuibonhoa/ruby-shoulda-tmbundle
 * HAML - http://github.com/phuibonhoa/handcrafted-haml-textmate-bundle
 * Sass - http://github.com/phuibonhoa/ruby-sass-tmbundle
 * JavaScript - http://github.com/phuibonhoa/Javascript-Bundle-Extension
 * CTags - http://github.com/phuibonhoa/tm-ctags-tmbundle

##Credits

Additions by [Philippe Huibonhoa](http://github.com/phuibonhoa)

Original Bundle Created by [Adam Stacoviak](http://www.adamstacoviak.com/ "Adam Stacoviak | Web Development, Interface Design, User Experience &amp; Internet Marketing"), co-founder of [Handcrafted](http://gethandcrafted.com/ "Handcrafted &ndash; Ruby on Rails Development Consulting Firm, Interface Design, User Experience, Web Marketing"), a Rails Development Consulting Firm.

Parts of this bundle were ported from the official Ruby Haml TextMate bundle. The filter snippets were ported from [Matt Polito's ruby-haml.tmbundle](http://github.com/mattpolito/ruby-haml.tmbundle/tree "mattpolito's ruby-haml.tmbundle at master - GitHub").

##Installation

1. $ `cd ~/Library/Application\ Support/TextMate/Bundles/`
2. $ `git clone git://github.com/handcrafted/handcrafted-haml-textmate-bundle.git Haml.tmbundle`
3. $ `osascript -e 'tell app "TextMate" to reload bundles'`