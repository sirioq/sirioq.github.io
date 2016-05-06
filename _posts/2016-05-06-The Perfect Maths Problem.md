# The Search for the Perfect Mathematical Problem.

Recently I've been looking through a number of maths problems from different sources, textbooks, Olympiad papers and 'recreational' mathematics books, in the hunt for what makes the perfect challenge.

It soon became apparent that for my purposes the problem needed to be easily accessible. There were a number of really engaging problems but the level of assumed mathematical knowledge was too great to have widespread appeal.

example:

find 
$$
i^i 
$$

$("script[type='math/tex']").replaceWith(
  function(){
    var tex = $(this).text();
    return "<span class=\"inline-equation\">" + 
           katex.renderToString(tex) +
           "</span>";
});

$("script[type='math/tex; mode=display']").replaceWith(
  function(){
    var tex = $(this).text();
    return "<div class=\"equation\">" + 
           katex.renderToString("\\displaystyle "+tex) +
           "</div>";
});
