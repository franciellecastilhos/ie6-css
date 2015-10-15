Universal Internet Explorer 6 CSS

How do you answer the Internet Explorer 6 question?

<ol>
<li>Design for better browsers, then design alternative solutions to handle IE6 bugs?</li>
<li>Write a remedial IE6 stylesheet to address layout issues?</li>
<li>Use JavaScript to bootstrap CSS support in IE6?</li>
<li>Make your site look <a href='http://dowebsitesneedtolookexactlythesameineverybrowser.com/'>exactly the same</a> in IE6 as in any other browser?</li>
<li>Develop to better browsers and spend no development time or testing for IE6?</li>
<li>Block IE6 users from seeing your site's styles?</li>
</ol>

<p>As <a href='http://twitter.com/adactio'>Jeremy</a> <a href='http://24ways.org/2008/the-ie6-equation'>wrote</a> last year.</p>

<blockquote>
<p>All of these different methods for dealing with IE6 demonstrate that there's no one single answer that works for everyone. This isn't a binary issue. There is no Boolean answer. Instead, there's a sliding scale of support:</p>
</blockquote>


<h4>Design for better browsers, then design alternative solutions to handle IE6 bugs</h4>
<p>I've often <a href='http://transcendingcss.com'>written</a> that designers shouldn't be limited by lowest common denominator browser capabilities. Instead they should design for the best browsers first, then design around issues presented by older, less capable browsers like Internet Explorer 6. The most important element in this approach is that web sites cannot, need not and should not look the same in all browsers.</p>

<h4>Write a remedial IE6 stylesheet to address layout issues</h4>
<p>A common approach to take; feed versions of Internet Explorer, including IE6, style-sheets that are necessary to override styles served to better browsers with the aim of working around Internet Explorer's bugs and hasLayout issues. This Conditional approach has few pitfalls, as long as you keep in mind that web sites cannot, need not and should not look the same in all browsers. Unfortunately many designers and developers use this approach and spend hours or days attempting the cross-browser, pixel-perfection that their clients still mistakenly expect.</p>

<h4>Use JavaScript to bootstrap CSS support in IE6</h4>
<p>This is an approach that I advocated in <a href='http://transcendingcss.com'>Transcending CSS</a>, recommending <a href='http://dean.edwards.name/'>Dean Edwards</a>' <a href='http://code.google.com/p/ie7-js/'>ie7-js scripts</a>. <a href='http://twitter.com/meyerweb'>Eric Meyer has also written that <a href='http://meyerweb.com/eric/thoughts/2008/10/22/javascript-will-save-us-all/'>JavaScript Will Save Us All</a> to &ldquo;use the browser’s JS to extend its CSS support&rdquo;. I still think that this is an option worth considering when circumstances demand and the additional weight of browser fixing scripts will not be cumbersome to the user experience.<br>
<br>
Unknown end tag for </p><br>
<br>
<br>
<br>
<h4>Make your site look exactly the same in IE6 as in any other browser</h4>
<p>Not only unnecessary and impractical, but unachievable. You need only look at the different ways that the Windows platform, Webkit browsers and Firefox render text to realize that even the simplest elements will, by definition, look different in various browsers. I'm convinced that professional designers and developers already know that this approach is flawed. Given the choice between spending their money on fixes for a diminishing browser or more design time, more functionality or more features, any client (usually the ones expect cross-browser perfection) will choose the latter. I think this will be particularly true in today's challenging economy.</p>

<h4>Develop to better browsers and spend no development time or testing for IE6</h4>
<p>While I fervently believe that by taking a progressive approach and designing for the best browsers first, client will get an overall better product, faster and for better value for money. That said, ignoring IE6 and its users, will likely result in a product that looks <em>broken</em> at best and is inaccessible at worst. No manager or owner wants a broken web page that reflects badly on their brand.</p>

<h4>Block IE6 users from seeing your site's styles</h4>
<p>Calls to <a href='http://www.bringdownie6.com/'>bring down IE</a> or for a <a href='http://iedeathmarch.org/'>death march</a> are popular (if unfortunately named) rallying cries. Some have valid points to make, others are <a href='http://ie6update.com/'>stupidly dishonest</a>. There are several situations that make it difficult or impossible for a person to update their browser, particularly in some business environments and in the developing world. By removing styles altogether so that a user sees only browser defaults will likely make that person think that the site, connection or their browser are broken or that they themselves have done something wrong.</p>

<p>Are these the only options? No. Because with a little creative thinking, some simple CSS and most importantly the understanding that not all browsers, especially older ones, need not see the same design, there is another way. That is why on all of my sites I will be serving one, standard, universal stylesheet for Internet Explorer 6.</p>

<h3>Universal Internet Explorer 6 CSS</h3>

<p>When I asked myself why people visit my sites, and the ones that I make for other people, the answer was always &ldquo;for the content&rdquo;. Content that is almost always written words and that means type.</p>

<p>That is why I'm now advocating to my clients (and to you), that where feasible, not to waste hours in time and a client's money on lengthy workarounds in an unnecessary attempt at cross-browser perfection. Instead, you and I should provide simple but effectively designed HTML elements. This means great typography for headings, paragraphs, quotations, lists, tables and forms and no styling of layout.</p>

<p>More than that, I intend to serve exactly the same Universal Internet Explorer 6 CSS for all sites (give or take a little branding here, or a touch of customization there). This will pay dividends for me, reduce wastage for my clients and give end-users a well-designed, well-presented view of what they come for &mdash; content.</p>

<p>You can view the <a href=''>Universal Internet Explorer 6 CSS file</a> or, to save you the trouble of opening IE6, <a href=''>this site's home page</a> as displayed using only the Universal Internet Explorer 6 CSS. If you're wondering how one single CSS file might render other sites, here is an article from <a href=''>Jason Santa Maria</a> and the <a href=''>A List Apart home page</a>.</p>

<p>Taking this one stage further, I have added Universal Internet Explorer 6 CSS to Google code and you can serve it from there, as I am doing.</p>

<p>I think that Universal Internet Explorer 6 CSS pushes all the right buttons as a concept, but of course this is only version one. I hope that you'll help me to make it better.</p>