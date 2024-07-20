# typographical edicts

People keep making fonts wrong, so here's my advice.

Advice for normal people:

1. The bars on the top and bottom of the capital I should always be present, even in a sans-serif font (hence why I just called them "bars" and not "serifs")
2. lowercase l, the numeral 1, and capital I *must* look different. Very distinct. You may type the phrase "11 Illicit Igloos" to test this.
3. in fact, ideally every glyph in your font looks distinct. This may mean that you have to represent EG the Cyrillic alphabet in a slightly different font than the Greek alphabet, but that's fine you just do that.
4. Non-lining numerals (https://en.wikipedia.org/wiki/non-lining_figures) just look ridiculous, and should not be used.
5. If you are designing a romanization scheme for a language, never use the dotless ı / dotted i distinction such as in Turkish and other similar languages. this will lead you into an incredible amount of technical trouble, where the very capitalization of i now depends on locale (something programmers are bad at thinking about). (For those curious, in the Turkish locale i becomes İ.)
6. italic should be a first-class citizen of unicode, as should bold.
7. everybody already knows this, but there is a difference between true italic and "oblique", where you just slant the letters a bit. (presumably there's a sort of type where you rotate all of the letters a little bit as well?) true italic is usually better; And it's always better if you actually want true italic instead of just a thing that vaguely looks like it a bit.
8. serif fonts are better than sans-serif fonts.
9. everybody is always trying to design a font that basically looks like helvetica. stop doing this. No one needs another helvetica.
10. in fact, If you could stop making fonts that are indistinguishable from other fonts we already have several variants of, that would be great. maybe instead you could actually make a single good serif font that covers every Unicode character so far, which I'm still trying to find tbh. (sometimes I think I will spend the rest of my life getting really into font design and then release an extrapolated version of the Georgia font over the entire Unicode character set (and also with lining numerals of course, instead of the current garbage) and call it Ultra-Georgia. (I pick Georgia because it was specially designed to display well on low resolution screens even though it has serifs, and they apparently did that very well because it looks great! unlike many others I've tried on crappy screens))
11. I probably prefer the sorts of Chinese/Japanese/etc fonts that look like they were manually written, a bit, Song/Ming fonts, over the sorts of fonts that look like they haven't been (Gothic), because it's apparently analogous to serif vs sans serif. i don't really know, though, because i don't read Chinese 

Novel advice:

1. There actually should be a devoted character for the apostrophe, which should not be confused with the single right quote, despite the fact that these are the same character in most traditional typography. They should not be the same character; they should be considered distinct characters instead. otherwise how are you going to know when a quotation stops? This dedicated apostrophe character should be somewhat curvy, but not as much as the single quote. But definitely more than the straight single quote! It also should not be confused with any other of the various marks that kind of look like a quotation mark or apostrophe. (Your best bet for this at the present time in unicode would be to use an apostrophe character ', style it with the font to be slightly curvy, and forget I said anything about "straight single quote" because obviously a straight quotemark is a contradiction in terms... a mad disease of the brain inspired by a lunacy caused by the dust of typewriters...)
2. Also, umlaut and diaeresis should be distinct. the umlaut should look more like ő, but not exactly. (there is technically a way in Unicode to indicate these two distinctly, as was required by a German library system)
3. I know people think there's technically a distinction between different types of dashes (en or smaller) and the hyphen and the minus, but I've never really found any of those useful. It is pretty crazy that the minus sign also looks exactly like the sign we use to make a numerical range like 1-10 (is that "1 to 10" or -9?). I'm sure the dashes help with that, if you know what the different dash lengths mean and read very carefully. (hint: minus is shorter)
4. typing the ^ above the o in the word rôle is unnecessary.
5. using the diaeresis in words like coöperate is usually unnecessary and out of style. in cases where it is necessary, it's probably clearer (to most readers) to use a hyphen like co-operate.

Blue-sky advice:

there should be an opening comma, a closing comma, and a list comma.

I think we need two additional marks that are like the M-Dash that are used when the M-Dash is used parenthetically (but not when it's used because the person is breaking off in speech never to return)

there can be a right-colon as well (possibly the direction of the colon should be reinforced by little triangles instead of dots)

the word i (first person pronoun) should not be capitalized. Was to make it clearer in handwriting, but now it's just less clear because I'm not sure if somebody is writing a one or if it's like the start of a different word or some part of something that's been capitalized for some reason like in a title or Roman numeral or something, more commonly now. just have it be a regular word that isn't capitalized. It's not like it's your name! me isn't capitalized.

i wnd j shouldn't have dots at all, actually. It's weird to have letters with disconnected elements so we shouldn't have them. horse might be out of the barn on that one though. Also in the time since I had this opinion advertised my opinion and I don't think it's bad to have these anymore.

instead of A through F, there should be designated hexadecimal digits. (in the optimal character encoding, byte values 00000000 to 00001111 would represent the digits from 0 to 15). they should probably be displayable on a 7-segment display, but i haven't figured out much else about them. They shouldn't be non-lining, though!

capital letters are unnecessary and could have been gotten rid of. or treated as a rich text styling! (again, though: horse, barn. at leaet with unicode)

too many punctuation marks are used for too many things. period shouldn't be used for both abbreviation and sentence-ending. It's ambiguous! there should be a special abbreviation mark I guess, or the sentence ending period should look different (perhaps be larger, like one of the Asian language periods, especially if we're not going to have capital letters anymore...)
