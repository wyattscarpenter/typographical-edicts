# typographical edicts

People keep making fonts wrong, so here's my advice.

Advice for normal people:

1. The bars on the top and bottom of the capital I should always be present, even in a sans-serif font (hence why I just called them "bars" and not "serifs").
2. lowercase l, the numeral 1, and capital I *must* look different. Very distinct. You may type the phrase "11 Illicit Igloos" to test this.
3. in fact, ideally every glyph in your font looks distinct. This may mean that you have to represent EG the Cyrillic alphabet in a slightly different style than the Greek alphabet, but that's fine you just do that. (Although, your font should also contemplate what happens when people italicize and blackletter-style your font, and all of those glyphs also look distinct from every other font — so your greek omicron shouldn't just be an italic latin o, for example.) (This becomes even harder when unicode adds characters to represent variantions in how letters look that you might have been depending on — like when they added unicode italics, for example ; or when they added ℴ (whatever that is).)
4. Non-lining numerals (https://en.wikipedia.org/wiki/non-lining_figures) just look ridiculous, and should not be used.
5. If you are designing a romanization scheme for a language, never use the dotless ı / dotted i distinction such as in Turkish and other similar languages. this will lead you into an incredible amount of technical trouble, where the very capitalization of i now depends on locale (something programmers are bad at thinking about). (For those curious, in the Turkish locale i becomes İ.)
6. italic should be a first-class citizen of unicode, as should bold. (Probably using variation selectors.)
7. everybody already knows this, but there is a difference between true italic and "oblique", where you just slant the letters a bit. (presumably there's a sort of type where you rotate all of the letters a little bit as well?) true italic is usually better; And it's always better if you actually want true italic instead of just a thing that vaguely looks like it a bit.
8. serif fonts are better than sans-serif fonts.
9. everybody is always trying to design a font that basically looks like helvetica. stop doing this. No one needs another helvetica.
10. in fact, If you could stop making fonts that are indistinguishable from other fonts we already have several variants of, that would be great. maybe instead you could actually make a single good serif font that covers every Unicode character so far, which I'm still trying to find tbh. (sometimes I think I will spend the rest of my life getting really into font design and then release an extrapolated version of the Georgia font over the entire Unicode character set (and also with lining numerals of course, instead of the current garbage) and call it Ultra-Georgia. (I pick Georgia because it was specially designed to display well on low resolution screens even though it has serifs, and they apparently did that very well because it looks great! unlike many others I've tried on crappy screens))
11. I probably prefer the sorts of Chinese/Japanese/etc fonts that look like they were manually written, a bit, Song/Ming fonts, over the sorts of fonts that look like they haven't been (Gothic), because it's apparently analogous to serif vs sans serif. i don't really know, though, because i don't read Chinese 
12. Text-processing systems (like markup) should respect it when you put in a newline, and not demand you put in two newlines to get a paragraph break. Similarly, the output of such systems should be typeset like regular text: pargraphs should be indented in the next line, instead of having a whole blank line separating paragraphs. (It's more important to have the beginning indent than to lose the blank line.)
13. There is a little difference of opinion on whether the first pargraph of a text should be indented (such as, the first paragraph of a chapter under its title) or left flush with the left side of the page. Well, my opinion is that YES it should be indented. You can also use an illuminated letter there if you would like.

Novel advice:

1. There actually should be a devoted character for the apostrophe, which should not be confused with the single right quote, despite the fact that these are the same character in most traditional typography. They should not be the same character; they should be considered distinct characters instead. otherwise how are you going to know when a quotation stops? This dedicated apostrophe character should be somewhat curvy, but not as much as the single quote. But definitely more than the straight single quote! It also should not be confused with any other of the various marks that kind of look like a quotation mark or apostrophe. (Your best bet for this at the present time in unicode would be to use an apostrophe character ', style it with the font to be slightly curvy, and forget I said anything about "straight single quote" because obviously a straight quotemark is a contradiction in terms... a mad disease of the brain inspired by a lunacy caused by the dust of typewriters...)
2. Also, umlaut and diaeresis should be distinct. the umlaut should look more like ő, but not exactly. (there is technically a way in Unicode to indicate these two distinctly, as was required by a German library system)
3. I know people think there's technically a distinction between different types of dashes (en or smaller) and the hyphen and the minus, but I've never really found any of those useful. It is pretty crazy that the minus sign also looks exactly like the sign we use to make a numerical range like 1-10 (is that "1 to 10" or -9?). I'm sure the dashes help with that, if you know what the different dash lengths mean and read very carefully. (hint: minus is shorter)
4. typing the ^ above the o in the word rôle is unnecessary.
5. using the diaeresis in words like coöperate is usually unnecessary and out of style. in cases where it is necessary, it's probably clearer (to most readers) to use a hyphen like co-operate.
6. You should be able to typeset (and, indeed, even play) music entirely from a unicode representation of the sheet music (again, probably using variation selectors.
7. there are textual characters that aren't in unicode yet, mostly because they haven't found enough dusty scholar manhours yet to get a comprehensive proposal together. for example, https://en.wikipedia.org/wiki/Maya_script#Computer_encoding . so, dream big.
8. there are also textual marks that will never make it to unicode, being the idiosyncratic marks of only one source. remember that.
9. It's probably better for the space after a sentence to be more than one regular space. i don't personally hit the space baar twice, but I see the appeal. i think it would probably be better at a 1.5 space I suppose. Maybe the period being small already does this.
10. You should endeavor to use whom correctly where appropriate.
11. You should pronounce the wh phoneme as it is supposed to be, as /ʍ/ (voiceless w). This is a little bit archaic in most dialects, but it's good, based on the principle that you should pronounce distinct words distinctly. you should also go even further than that and pronounce the w h in words like who and whole as /ʍ/; this was lost in Middle English, which I usually think of as too far back to revert a change on, but we can just start doing it again.

   

Blue-sky advice:

there should be an opening comma, a closing comma, and a list comma.

I think we need two additional marks that are like the M-Dash that are used when the M-Dash is used parenthetically (but not when it's used because the person is breaking off in speech never to return)

there can be a right-colon as well (possibly the direction of the colon should be reinforced by little triangles instead of dots)

the word i (first person pronoun) should not be capitalized. Was to make it clearer in handwriting, but now it's just less clear because I'm not sure if somebody is writing a one or if it's like the start of a different word or some part of something that's been capitalized for some reason like in a title or Roman numeral or something, more commonly now. just have it be a regular word that isn't capitalized. It's not like it's your name! me isn't capitalized.

i wnd j shouldn't have dots at all, actually. It's weird to have letters with disconnected elements so we shouldn't have them. horse might be out of the barn on that one though. Also in the time since I had this opinion advertised my opinion and I don't think it's bad to have these anymore.

instead of A through F, there should be designated hexadecimal digits. (in the optimal character encoding, byte values 00000000 to 00001111 would represent the digits from 0 to 15). they should probably be displayable on a 7-segment display, but i haven't figured out much else about them. They shouldn't be non-lining, though!

capital letters are unnecessary and could have been gotten rid of. or treated as a rich text styling! (again, though: horse, barn. at least with unicode)

it's also inconvenient to use capital letter for both proper nouns AND the beginning of sentences. ambiguous nouns can appear at the beginning of sentences! Probably, there should be a begin-sentence mark (unless the previous period is enough...) And also separate proper noun brackets, title brackets, and subtitle brackets. Like what the Japanese do around titles with their little quotation mark type things.

too many punctuation marks are used for too many things. period shouldn't be used for both abbreviation and sentence-ending. It's ambiguous! there should be a special abbreviation mark I guess, or the sentence ending period should look different (perhaps be larger, like one of the Asian language periods, especially if we're not going to have capital letters anymore...)

there should actually be one letter per sound and you should spell words by writing down exactly how you pronounce them. The spelling will change over time. So what? things already change over time.

If you do need to have a standardized spelling, you should have one that stays stable for exactly a hundred years and so you have a standardized spelling for X0XX, X1XX, and you can easily tell which dictionary to consult based on the date of the document.

Advice for programming? (coming soon?)

programming is traditionally done in monospace, which has the advantage that you can learn pretty easily where on the page your eyes should jump to to see things (i cannot prove this). it's also traditionally displayed on a screen in colored text, colored based on the syntax of the program language, which is good because it reminds you of the syntax of the programming language, and how this program fits into it.

i use a two-space indent, as the smallest power-of-two number if spaces visually distinguishable from a single space. But I get the feeling maybe I'm just I'm usually good and distinguishing this, which is why most people use four spaces. That also seems fine to me. everyone agrees eight space indents, which is traditional, is insane. You can also use tab characters to intent, which is kind of what you're supposed to do in a way, but the tab character basically got less and less supported as time went on due to historical accident so I don't think it's worth reviving it now.
(in any case, you should definitely have an auto formatting tool that can take care of this. including changing the tab sizes to whatever you prefer when you edit, and changing back to whatever your organization prefers once you're done editing. It should also handle removing trailing white space and ensuring there is exactly one new line at the end of files (a peculiar requirement of some things that handle files; which I follow for the sake of uniformity, even though I personally think of the new line character as a line separator and not a line terminator...)

digraphic programming fonts seem bad to me, but only because they tend to produce glyphs that are indistinguishable from other distinct characters that already actually exist, like →.

-> is an ugly little contrivance, and should not be used. same with <> for angle brackets. These also make parsing much more complex (although parsing should actually be trivial if you implement it correctly; this is just double the effort of trivial) because you can't count on > to be an operator any more. But this only matters if you're designing a programming language.

Pre-composed characters are the original sin of unicode, and should not have ever been. Just write the program to render the á, what's the problem? When they finally make a new unicode they shouldn't make this mistake again.

I used to think all accent marks were a mistake as well, and all of language should be monospaced by glyph, but that no-longer seems very realistic or desireable to me. They should be easier to type, though... (American keyboard user talking.)

It's weird that the ellipsis is made up of periods (which actually end the sentence more strongly than an ellipsis). A perfect punctuation system wouldn't do that. Also, there wouldn't be an ambiguity between trailing off and ellision of text, as there currently is with ... (the fact that … is a distinct unicode character doesn't really help, because it still looks like 3 periods.

You don't need me to tell you this, no one does any more, but it's crazy that typewriters just had you use the same character for 1 and l. How much money could that have possibly saved? And how much confusion did it incur? And it harmed typography for generations...

As far as I can tell, ligatures like ﬀ should never have been added to unicode, since they're just a font thing for ff. But maybe there's something I don't know about it.

If you were making a second unicode, you should definitely keep all of their wacky little symbols that they added into unicode despite not knowing what exactly they meant. Like ⍼ https://en.wikipedia.org/wiki/Angzarr. You don't have to keep the ones that are like "top half of integral" though. Or do you? Maybe someone has used that on a typewriter to make a really tall integral, with | as its backbone 🤔. You should definitely pick a more accurate name for ☫, though.

I would not have added emoji to unicode. That horse is out of that barn, though, I think. (I mean, I wouldn't have added them to the earlier text encodings that Unicode then endeavored to include, therefore starting the emoji craze.)
